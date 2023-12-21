In 2012/2013, I helped found a startup that focused on product identification of Pinterest images using computer vision and machine learning. In those days, convolution neural networks were still largely a guarded secret, with access to Google's DistBelief code (a private precursor to Tensorflow) being only wished for. MATLAB was the primary tool for which our small team of University of Toronto master students explored CNN with. I myself was writing our production code using Python-based SVMs, histograms, perceptual hashes, segmentation systems, and more.  


  

Those early days were confusing for me as the machine learning establishment was still fairly deeply entrenched in classical machine learning and computer vision approaches. CNNs were hard to understand, let alone give consideration to, and the lack of support available to guide me was virtually non-existent. In fact, I received quite a bit of push back in my deep belief that they were the future. I did receive support from two master student interns at that time, but their communication skills were abysmally absent.  


  


At the start of 2014 we brought on a Chief Science Officer to lead the growing research team, although computer hardware and deep learning were not his expertise. I was generally opposed to the cost of acquiring this CSO, feeling like we were investing into the wrong skill set, but it helped the investor story regardless and gave me the opportunity to focus on improving the production-systems.

  


2014 was the year we finally started to have some cash though, and the research team had started to grow into a small army; there was still very little effort put towards CNNs however. The R&D team would showcase improvements to the existing systems during our biweekly demo-days, but I mainly got empty responses when I talked neural networks. I felt then the best way to encourage the research team to try out neural networks more was to provide them with the tools to explore with.


  


The first system I bought for the team was an Intel-X79 based workstation with 64-GB of RAM, a Nvidia GTX 770 4GB, 240GB SSD, and 3-TB HDD. The system had as 1250-watt power supply and could be scaled up to house 4-GPUs if needed. I also made sure everyone on the R&D team, regardless of system or role, had an Nvidia GPU. The pick I made there was the Nvidia 750 Ti 2GB, as it had enough VRAM to tinker with and had support for the newer CUDA 3.5. 

  


Such systems and parts were easy purchases for me to make, going so far as to just walk down to the local computer store and putting the expense onto my own credit card. I was really hoping they would start using what I bought them and provide feedback that they needed more VRAM and more power... but it never happened. 

  


The real system I had in mind for the R&D team to train on, and for me to use in production model training, was quite a bit beefier and very expensive. I sought out and received approval for what I costed out to be a roughly $45,000: a 4-GPU system with quad-Nvidia Tesla V40 GPUs, each with 12-GB VRAM. I preemptively even had a small server room created to house it: air-conditioned and sound-dampened.  

  

I never pulled the trigger on the purchase though. With no feedback from the R&D team and their efforts being spent on super-pixel segmentation and who knows what else, I was becoming somewhat frustrated. My late evenings were spent trying to push the CNN path forward, hacking out my own CPU-based neural networks in Python, or trying to get what open-source neural network code existed to work on my system. I wanted to showcase how effective CNNs could be for our problem.

  


By mid-2014, a few months after the company I helped build went public, I was replaced by some ex-Microsoft executive in a show to investors against my will. The board had control of the company at this point, not me, and they wanted to put in place someone who they felt could scale the company faster I suppose. To add insult to injury, I was put in charge of what was called the "legacy platform", as my replacement intended to rebuild the entire system from the ground up with his own team of developers.

  


As quickly as I legally could, I exited the company, and at the end of 2014 I was on to another AI startup. In the following months, the R&D team was disbanded as my replacement could not understand any of the work being done by them. He chose instead to double down on using an army of humans, a hundred or so, to button-press all day on incoming product images. Cost of service went up, as did query response times, but hey, it worked. Kinda. A couple years later they outsourced to a competing company who had built CNNs to do proper image recognition work. I have no idea what happened to that army of humans; where their souls are now I hope are in a better place.  

  

In hindsight though, seemingly small failures on my part snowballed out of control very quickly. Trust in my abilities to tackle hard problems or to scale quickly help led to me being replaced, even though I feel my replacements were quite ill-suited. No one wants to hear a problem or product will take 2 to 5 years to finalize, nor does someone want to hear that you feel uncertain about your choices. 

  


  
