# A7 – [Linkage Mechanisms]

Research - 

The first part of the project was to find 2 styles of linkage mechanisms that were patented or developed in the past 5 years. After doing thorough research online, these are the two that I chose to include in my research. 

Mechanism 1. Monolithic Compliant Four-Bar Linkage -

  This mechanism replaces traditional multi-part revolute (pin) joints in a four-bar linkage with flexible flexure hinges integrated directly into a single 3D-printed body. An input segment receives linear or rotary force (e.g., from a tendon or worm gear), transferring motion across a flexible notch (the compliant joint) to move the coupler segment. Because the motion is achieved through elastic material deformation rather than pin rotation, the structure eliminates joint friction, wear, and mechanical backlash while providing built-in shock absorption when colliding with obstacles.

Picture - 

<img width="356" height="479" alt="image" src="https://github.com/user-attachments/assets/20d25a8c-d30d-4e62-94c1-750f245d2aff" />

The main use for this type of linkage is in the prosthetic industry as it is used for the finger joints of prosthetic hands to ensure that the prosthetic can withstand the wear and tear of everyday use. The elastic design allows for the prosthetics to handle impacts better than traditional pin joints. 

Another use for this linkage is use in robotic and manufacturing fields, specifically in the food and automation industry. The linkage is integrated into robotic fingers to help grab certain products and move them around and between conveyor belts. 

Mechanism 2 - Deployable Articulated Mast Linkage - 

This spatial mechanism consists of a series of interconnected scissor-like linkages and pivoted frame modules that fold into a compact 2D/3D block for storage and extend into a rigid 3D linear tower upon deployment. It utilizes a single-degree-of-freedom constraint: driving a single linear actuator at the base triggers a synchronized chain reaction that unfolds every connected frame segment simultaneously, reaching a high length-to-stowed-volume expansion ratio without requiring separate motors at every joint.

Picture - 

<img width="561" height="627" alt="image" src="https://github.com/user-attachments/assets/05ab227c-e075-481e-bfd2-dc81d358ebcc" />

Main uses for this technology: 

1. Aerospace and space industry - Applied in satellite structures as deployable booms, solar panel deployment trusses, and deep-space communication antenna masts that must fit inside tight rocket payload fairings during launch and extend fully in orbit.

Civil defense and Emergency Infrastructure - Used in mobile emergency response vehicles for rapidly deployable lighting towers, temporary cellular/radio communication masts, and retractable support beams during disaster recovery operations.

Credible References: 

Patented Compliant Linkage:

Akhtar, A., Bretl, T., & Choi, K. Y. (2021). Compliant four-bar linkage mechanism for a robotic finger. U.S. Patent No. 11,185,427 B2. Washington, DC: U.S. Patent and Trademark Office.

Patented Prosthetic Mechanism:

Akhtar, A., Bretl, T., & Choi, K. Y. (2024). Compliant four-bar linkage mechanism for a robotic finger. U.S. Patent No. 11,974,930 B2. Washington, DC: U.S. Patent and Trademark Office.

Published Spatial Mechanism Journal Article:

Cheng, P., Cao, W., Wang, T., & Chen, G. (2025). Design and Analysis of a New Deployable Articulated Mast Mechanism With Two-Dimensional Deploying-Folding Motion. ASME Journal of Mechanisms and Robotics, 17(2), Article 021005. https://doi.org/10.1115/1.4065795

Design - 

The design portion started with my brainstorming how I could make a linkage design from scratch in SolidWorks. I looked online at examples and saw what other people did in the past to determine the direction that I wanted to go in. I decided to go with a snap fit link design that would combine what I worked on last week with my new project. 

The first step was to design the linkage bars themselves - This is the longer of the two bars that I designed 

<img width="683" height="419" alt="Screenshot 2026-10-05 160123" src="https://github.com/user-attachments/assets/ff483f27-77ee-4a90-b58b-f0ecfe396026" />

I then extruded the linkage to the desired width - 

<img width="581" height="335" alt="Screenshot 2026-10-05 160149" src="https://github.com/user-attachments/assets/bfe3c0ba-7d3f-4285-a851-8ebd541bccc4" />

The next linkage bar is here - This is the shorter of the two bars 

<img width="614" height="390" alt="image" src="https://github.com/user-attachments/assets/e1259f1b-be6c-4488-902c-c1cf6659d3cb" />

The extrusion was the same for this piece because I wanted to maintain consistency within the parts - 

<img width="331" height="303" alt="image" src="https://github.com/user-attachments/assets/b8f13426-e3ba-4615-9cc3-474023133934" />

The next step was the design the pins that would link each piece together - 

I started with the base of the pin; this would end up giving the pin a lip so that it could sit up against the links flush and it also made the project look better 

<img width="404" height="296" alt="image" src="https://github.com/user-attachments/assets/c323edb7-9e96-49f2-8ee1-58cf0f93201f" />

Next, I made the inner diameter of the pin; this was the part that would actually be inside of the links in order to make the design fit together properly - This image shows the diameter and the extrusion distance in the same frame

<img width="507" height="280" alt="image" src="https://github.com/user-attachments/assets/facc4672-39f9-4dde-8b93-691dffee743e" />

Finally, I needed to design the base in which the links would attach to - this started with the bottom of the base to give the part something to stand on for display purposes 

<img width="753" height="389" alt="image" src="https://github.com/user-attachments/assets/ce311679-504d-47a0-99f0-811b769c4c65" />

I then made the pegs to which the links would attach to and extruded them 0.75 inches just to be safe and have extra room avaliable - 

<img width="815" height="395" alt="image" src="https://github.com/user-attachments/assets/5fe9c13d-041c-485c-acb3-91b1aa2d7bed" />

I then cut out the holes for the pin connections; I made these in the center of the extrusion to make sure that there was enough room around the holes so the links could fit - 

<img width="439" height="434" alt="image" src="https://github.com/user-attachments/assets/49fccb9f-f3a9-44fd-b749-f0c7493b18fc" />

The best part about this entire link system is that you can add as many links as you want and can just continually print more links and pins due to the symmetry in the design. Theoretically, you could add 100 links together and make all kinds of shapes whenever you want. 

Purpose - 

the purpose of this link mechanism is to function as a fidget to keep your brain busy while trying to focus on a mundane subject. I chose to design it because I see people constantly struggling to stay on task and I understand the feeling. The design also functions as a quiet distraction that will not interrupt everyone else around you like some other fidget devices may. 

Components - 
- Link 1 - longer of the 2 links; Printed
- link 2 - shorter of the 2 links; Printed
- Pin - pin to connect links together; Printed
- Base - base plate for all links to connect from; Printed

Tolerances - 

Pin-in-hole Fit: I designed this pin in hole fit with 10 thousandths of clearance as this is what I have discovered works the best with 3D printed parts from our previous projects and my own personal experience. The last project where I designed a snap fit, the 10 thousandths clearance is what the machine was capable of making without noticing any issues in the quality of the fit. 

Design Decisions - 

1. matching the longer pin length to the length of the holes between the base - this was done to allow for a single link to be placed at the bottom of the stack and to allow for a solid base to be formed if someone decided to make a large link project in the future. I chose this because the bigger the base could be, the better stability I was able to expect from the overall part.

2. The pin is 10 thousandths smaller than the holes in the links - this was chosen because of previous experience with tolerances and fits from our past projects and from my own expertise in the 3D printing field.

3. I made the second link shorter than the first - I chose to do this over making them all the same length because I liked the uniqueness to the design if the pieces were not always perfectly even. The number of styles and changes you can make with having 2 different size links allows for much more creativity when making your own piece. If the links were all the same length, then the design would only ever consist of many squares repeated over and over again. I am very happy with this decision, and I am glad that I thought of it before making my final rendition.

Final Assembly - Here are multiple pictures of the final assembly. I included multiple so that you can see how the part will move around once it is put together 

<img width="545" height="490" alt="image" src="https://github.com/user-attachments/assets/0c5b5bb8-f708-4c92-ba20-4090f9b7e990" />

<img width="599" height="491" alt="image" src="https://github.com/user-attachments/assets/c11699da-b7df-4117-985e-1757e0bb6a5f" />

<img width="497" height="436" alt="image" src="https://github.com/user-attachments/assets/efcbbc02-c15c-48ea-a909-ae712a031f39" />

There are multiple other ways to bend this piece as well, but those 3 pictures give you an idea of the range of motion of my part. 











