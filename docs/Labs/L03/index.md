# A3 – [Design Something Small]

Design - 

I originally wanted to design a pen holder that had an angle similar to the one on the example page because the "add plane" feature is something that I have not done a whole lot within SolidWorks. However, since the dimension constraints were limited to 0.5 inches tall, I had to switch gears and go with a simpler design in order to make a working model. 

This is the initial drawing of the outline of the pen holder, I made it a basic square because it would allow for me to actually see how the different types of infill would affect the print and whether or not they would provide a strong enough base to handle the weight of a pen. 

<img width="147" height="128" alt="image" src="https://github.com/user-attachments/assets/a45ddf99-14d7-4cd5-b3bc-4409f79e37ad" />

Next step was to extrude the base and make a 3D square out of it 


<img width="253" height="158" alt="image" src="https://github.com/user-attachments/assets/b1e5d4c0-39bf-4726-8edc-86987956e854" />

Then, I extruded a small circle in the middle that would end up becoming a hole for the pen to sit into


<img width="233" height="147" alt="image" src="https://github.com/user-attachments/assets/f7f494e2-a042-4de0-9bf9-0d5f0fb0b638" />

Lastly, I made an extruded cut just barely bigger than the pen itself in order to provide a tight tolerance and hopefully ensure success on the first attempt


<img width="227" height="209" alt="image" src="https://github.com/user-attachments/assets/591c4d09-7214-4e86-822d-87967db50f72" />

Research - 

Grid: this is a 2D lattice that connects lines at 90-degree angles perpendicular to each other. This infill is used because of its' fast print speeds and ability to work with many small to medium utility parts and pieces. Great for at-home printing and DIY projects. 

Concentric - Closed rings that mirror the outer walls of the part and repeat over and over again towards the middle of the piece. This infill is used mainly in parts that need to be flexible because it will bend evenly and help distribute that load over a larger surface area. Some people also enjoy how this infill looks when using transparent materials. 

Lightning - A tree-like support structure on the internal area of the parts, only used when necessary and designed for speed. People use this infill mostly for quick prototype printing or for decorative models of parts. This infill is strictly used for its speed, and it leaves the bottom of the parts completely hollow and only builds supports near the top where it is necessary. 

Preprocessing - 

Here is the imported .stl file in Prusa Slicer, I had no issues on this part. 


<img width="371" height="264" alt="image" src="https://github.com/user-attachments/assets/03e0bc95-6379-40fe-904c-325e9228661a" />

The build orientation was easy because I made the part with a large, flat bottom to print on. I had no need to scale the part as I created it perfectly to the maximum dimensions given in the project guidelines. 

I decided to go with Concentric infill because I have never used it before and I believed that it would have worked very well for my purposes. The original infill type was Grid. 

<img width="293" height="223" alt="image" src="https://github.com/user-attachments/assets/6be1d05a-170a-491b-b7d5-00a885bc8c38" />

For wall thickness, I decided to go with 0.2 inches because I wanted a thick base to be able to hold the pen because I expect it to get plenty of use and would hate to have it break over and over again. I also chose this wall thickness because when using concentric infill, making it 0.2 inches is the cutoff for an extra layer of infill. This alone helped to double the strength of the part that the pen would slide in to. 

The main mistake I ran into during the process was that I designed a complete part and then tried to change the dimensions of that part to fit the instructions. Since I originally chose an angle surface to make my extruded cut, the actual amount of material that would be able to hold the pen in place dropped by about 40%. I was not confident that it woulf actually hold the pen, so I decided to go in another direction, and I am glad that I did because the part came out great and actually works. 

Print - 

I like to look at the legend on Prusa Slicer because it provides a lot of detail about how the machine and software see each individual print. This picture also shows that my print time was 13 minutes, far below the cutoff for print times on this project. 

<img width="255" height="224" alt="image" src="https://github.com/user-attachments/assets/aaec83e8-5fc1-4f10-9b97-9a7433c573bc" />

Here is a picture of the printing in progress. With the amount of people standing around the printers and using them all at the same time, I did not get one of the infill, however it did come out very nice and I can tell a difference with how the part feels compared to the last part we made with the basic infill. 

<img width="660" height="1434" alt="IMG_5780 1" src="https://github.com/user-attachments/assets/dc708801-0587-44ec-953f-0edf0f9305ca" />

The part was made using PLA, it had no overhangs and the dimensions are 1.5" x 1.5" x 0.5" as limited by the project guidelines. 

Video - 



Lessons Learned - 

  1. In SolidWorks, the angled geometry is much easier to work with than I remember which was very nice.

  2. I wanted to try using a different file type, so for this file, I downloaded the .3mf file from Solid Works instead of using my normal .stl format that I am comfortable with. This worked out just as smoothly and I had no issues getting it to work.

  3. One thing I learned that can cause some issues is that if you have a different file type than your group members, sometimes Prusa Slicer doesn't like having a .STL and .3MF in the same slice. I could not figure out exactly why that was the case, but it was easier to just open Solid Works back up and re-download the file as .3MF to have our whole group on the same page.

  4. Sending the files as an email can take a long time. Next time I will make sure to have my flash drive with me because it reduces the need to wait around for an email to come through when I could just download the file on the drive from a group members computer and then plug it into mine.

Time to Completion - 2 hours

Resources - 

Google Gemini: for quicker help understanding infill types and uses 





