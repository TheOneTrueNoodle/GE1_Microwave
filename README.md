# SCI-FI Microwave!

Name: Ryan O'Connor, Erin Cooley

Student Number: C20409464, C20517416

Class Group: TU 984 (DT 508)

Video: 

[![YouTube](http://img.youtube.com/vi/GrGJKI5P_Zw/0.jpg)](https://www.youtube.com/watch?v=GrGJKI5P_Zw)

# Description of the project

We have created a futuristic household microwave, installed with a variety of strange holograms that can be interacted with that allow the microwave to fulfil a lot more than its normal duties. Investigate all of the different buttons on the microwave and see what cool effects are installed!

# Instructions for use

- The player must aim with either right or left hand and press the trigger and grip buttons to activate each microwave button
- each microwave button does something unique and shows a skill we have learned through programming!

# How it works

You can interact with the many buttons on the microwave to have many crazy affects happen, or simply cook up some grub. While there are limited options of food (due to neither of us being asset designers) the microwave has a number of features to distract you from the lack of food quality!!! Such as a stupid large tentacle hologram that appears from the top of the microwave, or if you really dont like the food that much... BLOW IT UP!!!

# List of classes/assets in the project

| Class/asset | Source |
|-----------|-----------|
| ColorChange.cs | Written by Ryan |
| Explode.cs | Written by Ryan |
| FoodSpawn.cs | Written by Ryan |
| NewInteractionScript.cs | Written by Ryan and Erin but never used fully |
| RotationPlates.cs | Written by Ryan |
| TextureChange.cs | Written by Ryan but not functional in vr |
| Banana.prefab | Made by Ryan using ProBuilder |
| RedBanana.prefab | made by Ryan using ProBuilder |
| Dream - Mask (Official Music Video).mp3 | [![YouTube](http://img.youtube.com/vi/Mu4wyzFQ_Ac/0.jpg)](https://www.youtube.com/watch?v=Mu4wyzFQ_Ac) |
| Hand.prefab | Made by Erin|
| tent of cal.fbx | Made by Erin|
| HoloGram Shader.shadergraph| Made by Erin|
| HologramColourScript.cs | Written by Erin|
| InteractScript.cs | Written by Erin|
| MicrowaveDoorScript.cs | Written by Erin|
| RaveCreationScript.cs | Written by Erin|
| RaveScript.cs | Written by Erin|
| TentacleAnimationScript.cs | Written by Erin|
| TentacleScript.cs | Written by Erin|

# References
* I[![YouTube](http://img.youtube.com/vi/Mu4wyzFQ_Ac/0.jpg)](https://www.youtube.com/watch?v=Mu4wyzFQ_Ac)

# What I am most proud of in the assignment

#### Ryan

Most of what I did in this project was pretty simple, and didnt cause any major difficulty nor did it feel like a major accomplishment. What I think I am most proud of from this assignment is learning how much I have developed and improved as a programmer over the last 2 and a half years since I started learning to program and getting to work on games with so many amazing people!

#### Erin

I was proud of the tentacle procedural animation i did, it was quite simple looking at it but looked like a very hard to do, im glad i finally achieved the ability to do it. i added a chain inverse kinematic to the tentacle so it follows the players hand like a friend.

# What I learned

While we learned a ton of useful skills around team management, individually we both learned seperate things

#### Ryan
For most of the development it was using my skills to make simple but also functional scripts that fulfilled the duty they needed to fulfill. I was able to experiment with particle affects and having an object break apart by activating seperate rigidbodies on the children of the parent rigidbody to cause the seperate pieces of a model to break apart. 

The biggest thing I learned was how to use UnityEvents in scripts. Ive used them before for UI but only for button interactions where they were already integrated. However, I now know how to reference UnityEvents so I can trigger any function on any script using a variable, without needing a direct reference to the specific script that the function is on. This will be a very useful tool in future games i develop in unity.

#### Erin

I learned the tentacle inverse kinematics and how to do animation rigging with procedural generation. Although i did have to model the tentacle i believe i would be able to fake bones and use just cubes next time, this would be proper.

# Proposal submitted earlier can go here:

Our plan is to have a very simple looking microwave, with an additional set of buttons that will create a rave like holographic effect. There will be a set of 10 buttons, with each button creating a different unique effect. The buttons development will each be seperated into their own branch. The buttons planned for the final submission are as followed:

Erin Buttons:
1. Creates a tentacle
2. Causes a disco inside the microwave (You are not invited and the food will have fun)
3. opens/closes the microwave door
4. Randomises hologram texture
5. Animates tentacle

Ryan Buttons:
1. Creates random food inside microwave
2. Rotates food inside microwave
3. Shoots food out the microwave (removes food)
4. Explode the food violently
5. Changes textures

The microwave will be interactable in VR! 
