CS 330: Computational Graphics and Visualization

My project’s a desk scene. It’s got a monitor, keyboard, mouse and black coffee mug and I built it in C++ with OpenGL using a photo that looked like my Mac setup as a reference.

How do I approach designing software?

I usually start by thinking about what I want the finished program to do and I work out the smaller problems as I move along with the big picture. The monitor was one example. I knew what one looked like but that didn’t tell me how to build it out of shapes. I used boxes for most of it and a tapered cylinder for the support. That made it easier to make changes because I could resize one piece without having to redo the rest.
The photo kept me focused. I tried a wood desk and an RGB pixel image on the screen but neither fit the scene I was trying to make so I took them out. It looked closer to the photo after that. I’d use a reference or a clear set of requirements again because I found it easy to spend time on details that didn’t help what I was making. Getting the shapes right helped too. Once I started adding textures I had less to go back and fix.


How do I approach developing programs?

I worked one part at a time and ran the scene after each change to make sure I was headed in the right direction. The code could build without errors but the keyboard could be in the wrong spot or the light could make the desk look blue. I had to check the scene itself and move the camera around to see if things made sense.

I used a photo of my keyboard for the keys so I didn’t have to build each one but I had to make the image fit the base. The plane was too big. I changed its size and ran the scene until the edges lined up. A lot of the project worked that way. I’d get something on the screen and use what I saw to figure out what needed to change.

The milestones helped me learn to test between changes because if I changed a texture and a light at the same time I couldn’t tell which one caused the problem. It made problems harder to track down. I moved texture loading, material settings and lights into their own functions so I knew where to look when I needed to change them. That made the work easier. Next time I’d group the drawing code by object too.


How can computer science help me in reaching my goals?

Working on this scene helped me connect the math to the code because I could change one number in an object’s position and watch it move across the desk. The numbers meant something now. I need more practice with rotations but I’ve got something I can picture when they come up in another class.
I want to use what I’ve learned in my Unity game. Choosing the texture isn’t enough. The light and material settings can change how an object looks so swapping out the image won’t solve the problem if those settings are what’s causing it. The monitor’s aluminum taught me that. I spent time working out why it didn’t look the way I wanted.

Performance is something I want to learn more about because I’ll have to make choices about how much detail I can keep when I build a larger game environment. The mug handle was a start. I cut down its segments to meet the triangle limit and it kept the shape it needed. This course gave me practice making those choices. It’s also made me want to understand what happens behind the tools I use so I can build or fix programs that display 3D objects in future classes and at work.
