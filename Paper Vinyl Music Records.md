Curious, but how many of you ever have used a vinyl record before? Im only 24 years old, but I recall the many nights when I was much younger, sitting at my dad's stereo, going thru his record collection, and loving it. Don McLean's American Pie, Tchaivosky's 1812 Overture, or Anne Murray, as some examples that just made a cold winter's night feel warm by listening too.  
  
In this modern day and age, things have become digital. Digital media. The closest we have to vinyl records today are compact discs, and as amazing as that is, sometimes it's simply too perfect. Sometimes a bit of the old fashioned is where it's at. Sometimes a bit of steampunk is needed.  
  
[![](http://bp2.blogger.com/_kfv2ADnjgQg/RtzuHd1bCfI/AAAAAAAAAEE/m-tp7RUU4x8/s400/sohappy.bmp)](http://bp2.blogger.com/_kfv2ADnjgQg/RtzuHd1bCfI/AAAAAAAAAEE/m-tp7RUU4x8/s1600-h/sohappy.bmp)  
*Here is an example of a type of vinyl paper record I have designed.*  
  
let me introduce you to a project I worked on a little while ago -- paper records. How cool would it be to simply 'print' out music? Sharing music as an image or on paper. A band could 'publish' their music in a local newspaper, or hand out flyers with their music printed on. Distribution of music would be even better than that of downloading online or via USB stick for bands. why? Because it's cheaper than any other physical medium to hand out when in the 'real' world and it really is easier to get it than having to remember to go online, search, and then download it later if told to.   
  
How does one play paper records though? One way could be to make a paper record player, which could be made very easily. modifying an optical mouse sensor to fit onto a normal vinyl records player would do it, or scanning it into a computer, with software to play the image, would do it. Hell, with everyone having a MP camera phone these days, you could just take a photo of the paper record and play it from that -- much like a barcode scanner does with a barcode. Imagine band posters posted up on the street posts, with their top single printed out on them as a paper vinyl, ready to be played by any camera phone, by simply taking a photo of the poster. No internet needed. No searching needed. and Instant.  
  
Take for example the above image...  
  
It's a song, @ 11khz,mono, and 8bits, if I recall right. It is crude, but it works. I can print this image out, and using a two megapixel camera, photograph the paper image, load the photo onto my computer, and play it back. It is definitly audiable, although some noise reduction will be needed to make it sound better, but still, it works.  
  

> im=imread('c:\sohappy.bmp');  
>   
> pi = 3.14159265  
> w=2;  
> c=1;  
> y=0;  
> z=1;  
> x=0;  
>   
> for z=200:w:min(size(im))/2-ceil(w/2)  
> zz=round((z+w)\*2\*pi);  
> x=0:zz;  
> r=z+w\*x/zz-1;  
> xx=x\*2\*pi/zz;  
> r1=round(r.\*sin(xx))+497;  
> r2=round(r.\*cos(xx))+497;  
> for x=1:zz+1  
> y(1,c)=im(r1(x),r2(x));  
> c=c+1;  
> end;  
> z % counts to about 500.  
> end;  
> y=y-min(y);  
> y=y/max(y);  
>   
> sound(y);

  
  
  
So above is the code for playback, using MATLAB (or SCILAB - free!).   
  
It can be compiled into a single EXE for independent execution if needed. The code is highly unoptimized and rather simple, so feel free to change it and experiment as needed.   
  
How does it work? Just like how a vinyl record or CD works, except data is stored in the level of shading per pixel. The whiter something is, the higher the frequency it will be. The audio is then written linearly in a spiral, in to out. Simple.  
  
More advanced software for playback will be able to automatically correct for distortion, determine playback variables, and normalize the sound.  
  
[Click Here](http://5.download-2.files-upload.com/50/2007/09/04/06-30/happy.wav) to download the resulting sound file when converted from a paper record!  
  
(yes, it ain't pretty, but there is LOTS of room for improvement.)  
  
I shall keep this updated with my own progress on this project.  
  
-steve  
  
p.s.  
To those who plan on leaving a comment, please do not leave derogatory messages. Helpful critiques, comments, or suggestions are welcomed though. thanks!