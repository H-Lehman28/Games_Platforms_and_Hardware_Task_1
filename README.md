# Games_Platforms_&_Hardware_Task_1

**Student Name:** Harry Lehman

**Student ID:** 2407002

For this task I was instructed to create a scalable foundation for a PC game, addressing issues such as resolution & aspect ratios, graphics scalability and dynamic input mapping.

<a href="https://ibb.co/DDVk2xCh"><img src="https://i.ibb.co/PZm4H7hK/Screenshot-2026-10-07-220858.png" alt="Screenshot-2026-10-07-220858" border="0"></a>

For the graphics scalability and the variable resolutions, I made a simple pause menu with buttons that allow you to change the graphics quality and the screeen resolution.

<a href="https://ibb.co/sv3HpJbt"><img src="https://i.ibb.co/kgc1V65M/Screenshot-2026-10-07-220634.png" alt="Screenshot-2026-10-07-220634" border="0"></a>

The resolution buttons change the resolution when pressed to one of three different standard screen resolutions; 1080p (1920x1080), 1440p (2560x1440), or 720p (1280x720).

<a href="https://ibb.co/GfxVXfYM"><img src="https://i.ibb.co/Kc09Yc4s/Screenshot-2026-10-07-220817.png" alt="Screenshot-2026-10-07-220817" border="0"></a>

The graphics setting buttons simply change the overall scalability level in Unreal Engine's built in scalability system. The buttons for Low, Medium, High and Ultra graphics set the scalability level to 0, 1, 2 or 3 respectively, which adjusted graphics settings such as shadow quality, texture resolutions and anti-aliasing.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/JRJzMM8s/Screenshot-2026-10-07-221019.png" alt="Screenshot 2026 10 07 221019" border="0"></a>

To test dynamic input mapping, I created a basic interaction system with a collectable that would function with both mouse & keyboard controls and a gamepad. I started by creating an input action for interaction and giving it button mappings for both control types, E for mouse & keyboard and the left face button for gamepad.

<a href="https://ibb.co/qLTrsH1j"><img src="https://i.ibb.co/Psq6h2Cj/Screenshot-2026-10-07-221051.png" alt="Screenshot-2026-10-07-221051" border="0"></a>

<a href="https://ibb.co/fVk4YSLD"><img src="https://i.ibb.co/Fk5gbWCH/Screenshot-2026-10-07-221137.png" alt="Screenshot-2026-10-07-221137" border="0"></a>

After assigning the buttons to the input action, I created a simple interaction system where if the player is in range of the collectable, they can press the interact button to pick up the collectable.

Video Demonstration: https://file.garden/al1RhDmrxi0o9o3H/Screen%20Recording%202026-10-07%20224553.mp4