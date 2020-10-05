# VR-project-1

 My room during covid pandemic
 
Demo: https://malathi74.github.io/VR-project-1/

Video link:

# Advantages of this project:

1.The basics of Three.js and A-Frame

2.How to bind objects to JavaScript functions (using onlick="functionName()")

3.How the Document Object Model works (DOM)

4.Front-end design techniques that greatly take into consideration UX

5.How to manipulate 3-D .gltf models

6.General JavaScript library usage

# Challenges Faced:

1.I have taken long time to position models but later I was able to do quickly because of practise

2.I have tried to play TV but sometimes video is not displaying. still I need to check this issue.


# Contributors:

Individual project; All work was completed by Malathi Kadipikonda.

# Work Distribution

Individual project

# Description:

I have created a room where i have been during lockdown of covid19. I have added items TV,computer,speakers,bicycle,sofa, decorated items, clock, fan, light etc. which were in my room.

This is room overview.

![Capture1](https://user-images.githubusercontent.com/72331508/95030611-8576e000-0676-11eb-934e-7efbc2f389f5.PNG)

To create walls, a-box tag was used and also it was given specific attributes to sorround the floor, and it was also given a texture

![wall](https://user-images.githubusercontent.com/72331508/95030654-c40c9a80-0676-11eb-867b-8ee6e5aa0b8f.PNG)

models were used to fill the house, and they were loaded using obj-model tag with appropiate attributes such as, position, rotation, scale, etc

1.Sofa

2.Window

3.Ceiling_fan

4.OfficeChair 

5.MonitorLCD

6.Clock

7.Smallbookshelves

8.Speaker

9.Bicycle

10.Bed

11.Plant

Example:
                        <a-obj-model
                            src="#window"
                            mtl="#windowm"
                            scale="1.0 1.0 1.0"
                            position="40.000 6.00 -15.00"
                                     rotation="0 180 0">
                        </a-obj-model>
