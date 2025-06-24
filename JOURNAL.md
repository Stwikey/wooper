---
title: Wooper
author: slack username is "@e"
description: A robot wooper that sits on your shoulder!
created_at: 2025-06-17
---

# June 17th: 3D Modeled the Wooper Head

I started to 3D model the case for the robot in blender. I have never used blender before so it was kind of difficult to figure out how to use all the different modifiers and I probably ended up restarting it like 3 times because I didnt know how to revert all my changes. I tried to use different modifies such as shrinkwrap but I didn't really understand it so I just stuck with the basics of subdivision surface and mirror. I kept just using extrude and scale to resize and adjust the model until it looked a little bit like wooper and managed to finish the head today!
<img width="1440" alt="Screenshot 2025-06-17 at 10 36 54 PM" src="https://github.com/user-attachments/assets/0c2f3c2b-4fd3-4f42-ba4e-ef9d049b3899" />
<img width="1440" alt="Screenshot 2025-06-17 at 10 37 02 PM" src="https://github.com/user-attachments/assets/99275e50-3ed7-49d2-a5a4-dd798c83bb33" />

**Total time spent: 3h**

# June 18th: Finished Wiring Diagram

I started to do the wiring diagram on KiCad since thats what I used for my hackpad and I thoguht it looked nice. I spent a lot of time trying to find the symbols for different components online but gave up around 2 hours in since I couldn't find most of the symbols for the components which I probably could've figured that out sooner.

<img width="798" alt="Screenshot 2025-06-18 at 10 13 52 PM" src="https://github.com/user-attachments/assets/fe536c26-6ef3-49d8-834d-08d1fc5988a4" />

I ended up using cirkit designer which was simpler and helped a lot with the visuals. I haven't used most of these components before so it was pretty time consuming researching how to wire up all the components and making sure that each component received enough voltage and current to function properly. 

<img width="572" alt="Screenshot 2025-06-18 at 10 15 28 PM" src="https://github.com/user-attachments/assets/a7e40454-4b30-4b24-8ce5-6d26dc251abc" />

Some of the features include:
- 2x MG90S servo motors to move the head side to side and up and down since I'm worried about the weight of the head
- 3x SG90S servo motors to move the tail, left, and right foot (1 each)
- 1x Submersible water pump to shoot water
- DFPlayer Mini Mp3 Player to play sounds
- Switch that powers it on and off

**Total time spent: 3h**

# June 23th: Finished the 3D Model (Mostly)

I finished modeling the body on blender but I still need to add wall thickness and add other mechanisms for the motors on the inside. I had issues importing the blender objects into fusion (the sizing wasn't correct) which I will figure out tomorrow and I still have to figure out a way to make the moving parts rotate without causing a lot of friction. For now the idea is to put a little gap between the parts so that they won't actually be touching.

<img width="1424" alt="Screenshot 2025-06-23 at 11 13 48 PM" src="https://github.com/user-attachments/assets/12c8b6ce-c550-4498-9f62-19baf187e266" />
<img width="1408" alt="Screenshot 2025-06-23 at 11 13 54 PM" src="https://github.com/user-attachments/assets/13456e8e-8c65-4398-ae50-8672f00f80ce" />


**Total time spent: 2h**
