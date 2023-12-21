# The Hard Drive Capacity Calculator

*Author: Steve*
*Published on: 2007-08-07T00:54:00.000-04:00*

---

Curious why when you buy an iPod, computer hard drive, or memory stick there is less memory actually available then what was advertised?  
  
For example, you buy a new laptop, advertised having 100GB of hard drive space, actually only seems to have 93GB available? It almost seems as if there is false advertising involved. I'm sorry to say, this isn't the case, rather just a tricky usage of terminology used by memory manufactures. Let me try to explain...  
  
You see, digital data is of binary numbers. 1's and 0's, also called bits. A group of eight (8 bits) 1's or/and 0's describe what is known as a byte. There are hence, 256 different values for a byte. ie: 00000000, 00000001, 00000010, 00000011, ... 11111110, 11111111. Digital memory is measured in the number of bytes, although it can also be described in bits.  
  
This is where it gets a bit more confusing....  
  
Just as with our decimal number system, when a very large binary number needs to be described, such as 123,456,789 Bits, we can use Metric prefixes (Kilo, Mega, Giga) to simplify things for us.  
  
For example, 123,456,789 Bits is also equal to ~ 123.46 Megabits or 123,456.89 Kilobits.  
  
Mega = Million  
Kilo=Thousand  
Giga=Billion  
  
This is how hard drive manufactures define memory sizes. Pretty easy, right? Well, sorta, this is where it gets a bit complicated.  
  
Since the start of computers, it has been common practice to define computer memory in powers of two, since computer memory is binary. For computer programmers, this is, for one reason or another, more practical and accepted.  
  
2^1=2  
2^8=256  
2^10=1024  
  
1000 is not a power of 2. 1024 is however. Since 1000 and 1024 are close to the same in value, to use the metric prefix 'Kilo' to define 2^10 just became accepted. Overtime, memory sizes grew. Mega came to define 1024 Kilos, or 1024x1024. Giga came to describe 1024 x 1024 x 1024... or 1,073,741,824. A bit different than 1,000,000,000 that we are accustomed Mega meaning  
  
Windows, MacOS, the iPod, as well as other devices and software, assume 1 kilobyte = 1024 byte. Hard drive manufactures, not liking this measurement system, have decided to define 1 kilobyte as 1000 bytes. 24 bytes smaller than what is actually considered a Kilobyte, making their storage devices and hard drives seem to have more memory on them then what is actually understood to be there. They are technically correct with their labelling, but it is using the abnormal definition of what a Kilobyte is considered.  
  
How do you distinguish between the two? Some have tried to define a difference by capitalizing one and not the other, but that idea seems to have failed in implementation. Capitilization does seem to work though in regards to differentiating between bits and Bytes though. Some add an extra letter to help define it, such as GiB, but it seems to be uncommon.   
  
Generally, hard drives and most memory devices use the 1000 definition, and everyone else uses 1024 to define a kilo. Until that changes, that is just a fact we will all have to deal with.   
  
Below is a simple tool you can use to discover the actual size of a drive based apon what the drive manufacture labelled it as. ---------------------------------------------------------------  
  
GB\*Labelled Drive Size<==>GBActual Drive Size--------------------------------------------------------------------------------------------------------------------------------------------------  
(\* GB = 1,000,000,000)  
  
For the sake of ceasing this continuing fight, maybe it be easier if Windows just started displaying memory as 1000 multiples, instead of 1024. Anyone who needs to know data in binary powers are surely smart enough to be able to do the math themselves. and not be being using Windows anyways. :)