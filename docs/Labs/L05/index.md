# A5 – [Design A Snap Fit]

Instructions - 

For this assignment I was tasked to design a snap fit that could be made and printed in PLA or PETG. This assignment was exciting because I had never personally designed something like this and made it. It felt like a big step in short (so far) design career, however, it definitely came with some learning curves. I failed multiple times trying to make this snap fit and for some reason I struggled to grasp this project to begin with. With that said, I did still enjoy this project because it made me feel more like an actual engineer in the scope of having to learn how to make parts from scratch with no prior knowledge, deal with repeated failure, and to learn something new at the end of the day. 

Modeling - 

My modeling was all done using the original numbers that I designed the part for. There was no need to change these calculations because these numbers were based on exterior forces and did not take into account the error that I eventually made which had to do with spacing between parts. 

<img width="431" height="444" alt="image" src="https://github.com/user-attachments/assets/b87df5ff-930b-4bf6-889d-e449c6366a41" />

As seen above, the stresses were much less than the maximum allowed stress and I should expect no issues with using PLA for this project. 

FBD's - 

<img width="415" height="566" alt="image" src="https://github.com/user-attachments/assets/f548857b-9557-43e0-9df5-e5a10b8f6675" />


Parametrically Design - 

Parameters Used: 

  -beam length

  - Thickness

  - hook depth

  - clearance

I chose these parameters because they give an overall encompassing guide to how a snap fit design works and they are the most important piece of the puzzle when starting with snap fit design. The other possibilities are a little more minor and were not seen as super important to gain the understanding of how the design is supposed to work. 

Length = 0.5in
Thickness = 0.1in 
Hook depth = 0.25in
Clearance = 0.05in

These values changed a lot throughout the process as I had a failure on my first attempt to complete this lab. The original design took about an hour to print and the secondary one was about half of that time. 

I started with an idea of how I wanted to make the part, but I really wasn't sure exactly where to go. So, I decided to just start making a design in SolidWorks to be the shell for the snap fit. 

The first step was to start with my piece that would snap into the other. In my case, it looked like a key. 

<img width="430" height="366" alt="Screenshot 2026-09-17 132148" src="https://github.com/user-attachments/assets/5fb7e731-69f0-48ae-a3aa-f424f747dc77" />

Parametric design was used on this part as seen in the next step. 

<img width="274" height="305" alt="Screenshot 2026-09-17 132248" src="https://github.com/user-attachments/assets/44bcbd3c-add9-4bba-a5da-a59fdd3eaa29" />

I will go through this part quickly because I had a major failure coming in my future that I was not ready for. the next part was designed without leaving enough room for the tab on the end of the snap fit to work. I will show a few pictures of the finished product since the design process was a failure. 

<img width="137" height="158" alt="image" src="https://github.com/user-attachments/assets/f017599c-df20-4956-88dc-d7ce955db4db" />

The above image shows how it looked in the Prusa slicer before I made my first print. This ended up breaking as soon as I tried to use the snap fit feature so I didn't want to waste a bunch of time covering this design with pictures. 

Here is where I moved towards the secondary option and made a whole new design hoping that this one would not fail. 

<img width="455" height="425" alt="Screenshot 2026-09-22 104739" src="https://github.com/user-attachments/assets/4452bf2e-58a6-4657-bedd-9ddda122002d" />

After seeing how much extra wasted space there was with the new design, I shrank it down to a much smaller piece

<img width="271" height="298" alt="Screenshot 2026-09-22 104946" src="https://github.com/user-attachments/assets/6241157b-a0f5-4d22-80f0-cbbb0a79322a" />

Then I cut a hole into the side to help release the snap fit once it went in. 

<img width="255" height="296" alt="Screenshot 2026-09-22 105057" src="https://github.com/user-attachments/assets/259b7228-e93a-42f7-97cc-b9ef6c2f878f" />

Finally, I put sides on the part so the snap fit couldn't slide out of it. I also made sure that the sides did not connect to the tab on the outside because last time I believe that was one of the reasons I had a bad fail. It added too much structural rigidity to the tab which caused it to snap and break instead of bend like I wanted it to. 

<img width="318" height="353" alt="Screenshot 2026-09-22 105655" src="https://github.com/user-attachments/assets/9a6c8e41-458a-478a-b7f6-850fdaff55cf" />

3D Print and Test - 

Pre-Processor layout:

This step was pretty simple for my part since I had flat surfaces on which the parts could print much easier. Much of this was thought of during the design process in order to provide a more seamless printing experience. 

<img width="524" height="301" alt="Screenshot 2026-09-17 140423" src="https://github.com/user-attachments/assets/8211f0e3-0072-4ac3-9ba9-bca63de64cf4" />

I was able to get away from using supports because my design did not have any major overhangs or areas where the machines limits would be tested. 

The main reasons for my build orientation are simple but precise 

The key is printed laying down because it is one solid piece that prints best with more material touching the printing plate. 

The snap fit piece was printed standing up because of the gaps in between the outside covers. If I had printed this piece on its' side, the overhangs would have likely caused it to fail. 

Slicer settings here - 

I kept the setting mostly at stock configuration, but I decided to add a larger brim to ensure better contact with the printing plate. 

<img width="525" height="279" alt="Screenshot 2026-09-22 114117" src="https://github.com/user-attachments/assets/b0995220-4438-4d2e-9d7a-3f935baa42d0" />

<img width="362" height="98" alt="Screenshot 2026-09-22 114122" src="https://github.com/user-attachments/assets/cef8483b-50ba-4e2a-aad0-84e62943ee89" />

The major mistakes that I had during this process was the testing part of my first design. 

As I tried to snap the pieces into each other, I exceeded the maximum deflection of PLA and sent the tab on my snap fit piece flying across the additive manufacturing lab and almost took out a fellow student... * OOPS * 

Luckily nothing got hurt besides my feelings because I thought I was done with the project until my part exploded. 

For my second design, the settings and layouts stayed the same as before because that was not the issue. 

<img width="434" height="245" alt="Screenshot 2026-09-22 112423" src="https://github.com/user-attachments/assets/a5e6d9a2-349f-45a8-83e4-a348e5b12c22" />

<img width="252" height="213" alt="Screenshot 2026-09-22 112434" src="https://github.com/user-attachments/assets/1f369f36-51f1-4298-81f6-c7e6ce2e6c1b" />

Research - 

Source - Eryıldız, M. (2021). Effect of Build Orientation on Mechanical Behaviour and Build Time of FDM 3D-Printed PLA Parts: An Experimental Investigation. European Mechanical Science, 5(3), 116–120.

Experimental research on FDM-printed PLA components demonstrates that build orientation is a critical factor governing flexural strength due to material makeup (Eryıldız, 2021). According to the study, parts printed in flat or horizontal orientations exhibit significantly higher tensile and flexural strength compared to upright orientations—which showed up to a 36% reduction in tensile capacity and increased susceptibility to premature failure. This occurs because horizontal printing aligns the principal bending stresses along continuous, extruded filament lines in the X-Y plane, placing the primary loading in tension and compression along the polymer strands. In contrast, an upright orientation forces bending moments to act perpendicular to the layer interfaces, subjecting the weaker inter-layer bonds to tensile separation and shear stress. Consequently, my chosen orientation to print the flexure cantilever flat on the build plate directly aligns with academic research, ensuring the beam handles maximum deflection without risking inter-layer delamination at the root.





This project has taken about 7 hours to complete due to the failure at the end of the first designs testing. 
