# camera habit tracker

## concept:
Creating a habit tracker that films a room with a raspberry pi camera module and tracks what a person is spending time on, this data is then processed by a program on the raspberry pi by using a trained AI image detection model. The data generated from this will be sent to a server. The server then takes the information and transforms it into a graph to show what activities have been done and how much time has been spent on each activity.

## Goals:
The goal is to have a working prototype that is able to differentiate two or more activities, to record the time spent on each activity and to send this information to a computer on which the graph can be made.

## Inspiration:
I was inspired to start this project by participating in a elective at my study where the task was to come up with, and create any IoT project. After doing some research I found that most sample IoT projects were things that didn't interest me or couldn't have the slightest impact in my life. 

I had to think of something myself. Luckily I stumbled across a AI hat for the pi, sold in a kit which came with a camera module. This got me thinking "what could I do with this and what things would I like it to assist me with?". Then it hit me, I've tried a few habit trackers on my phone, but I stopped using them because I disliked having to use my phone 20 times a day just to track my habits. What can I do about that? For this project I chose to track it in a way that allowed me to track habits in my most used room (which could be my whole house with a few more cameras) without having to do anything for it.

## Process:
I've started by ordering the neccesary components, after which the waiting started. Trying to use my time efficiently I decided to start doing some research on how to connect the components, and how to train a model using the pi hat and the camera.

## Outcome:

## Next steps:
1. Order components (Adafruit BrainCraft HAT + Raspberry Pi Camera Module V2)
2. Research on how to create models with the BrainCraft hat, and on how model creation works
3. Connect components and create a simple webserver for the raspberry pi to communicate with
