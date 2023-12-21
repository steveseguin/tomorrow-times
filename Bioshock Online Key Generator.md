still much a work in progress... but here it is.  
  
  
var msg = "";function generateserial() {msg="";var randomnumber=0; randomnumber=Math.floor(Math.random()\*4)+1; for (var x = 1; x <= 4; x++) { if (randomnumber!=x) { msg=msg+String.fromCharCode(Math.floor(Math.random()\*26)+65); } else { msg=msg+Math.floor(Math.random()\*10); } } msg = msg + "-"; randomnumber=Math.floor(Math.random()\*3)+2; for (var x = 1; x <= 4; x++) { if (randomnumber!=x) { msg=msg+String.fromCharCode(Math.floor(Math.random()\*26)+65); } else { msg=msg+Math.floor(Math.random()\*10); } } msg = msg + "-"; randomnumber=(Math.floor(Math.random()\*2)+1)\*2; for (var x = 1; x <= 4; x++) { if (randomnumber!=x) { msg=msg+String.fromCharCode(Math.floor(Math.random()\*26)+65); } else { msg=msg+Math.floor(Math.random()\*10); } } msg = msg + "-"; randomnumber=Math.floor(Math.random()\*1)+2;for (var x = 1; x <= 4; x++) { if (randomnumber!=x) { msg=msg+String.fromCharCode(Math.floor(Math.random()\*26)+65); } else { msg=msg+Math.floor(Math.random()\*10); } } msg = msg + "-";randomnumber=Math.floor(Math.random()\*1)+3;for (var x = 1; x <= 4; x++) { if (randomnumber!=x) { msg=msg+String.fromCharCode(Math.floor(Math.random()\*26)+65) } else { msg=msg+Math.floor(Math.random()\*10); } } document.getElementById("serial").value = msg;}GO  
  
  
As far as I can tell, you gotta be having one hell of a lucky day to have this work for you though. as i get more info on the algorithm, i'll update this one.  
  
(lol, sounds a bit crazed, but sharing with me valid keys, will greatly help me optimize this keygen.)