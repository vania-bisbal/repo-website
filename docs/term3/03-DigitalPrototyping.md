# Module 4: Sensing the body
About Citlali Hernandez <br>
https://turbulente.net/ <br>
citlali.hs@gmail.com <br>

## Resources_
- https://direct.mit.edu/books/book/4296/Affective-Computing
- https://iclc.toplap.org/2023/index.html is the Live coding conference
- http://www.wekinator.org/ by Rebecca Fiebrink 
- Course machine learning for musicians and artists - KAdenze by Rebecca Fiebrink 
- https://marijebaalman.eu/projects.html
## Recommended books_
- [Atlas of emotions](https://atlasofemotions.org/)
- Understanding emotions - Paul ekman 


## Concepts introduced during the session_
What is the body: medium or tool of expression AND is also a topic of research
She does performance art. The body is political and the body has something to tell. 
If the body is a territorry that we inhabit, how do we connect with it. 
Data can be translated into other types of signals. 
Emojis as a way of communication. 
What makes us emotional? physical event, social interactions, remembering/imagining specific event, etc. 
*Affective Computing*
*Robotics* Madeline Ganon - make the robot move using a natural language that we can understand
*Expresivity in human environments*: Digit - Agility Robotics


## Some inspiring projects_
- Live coding: visuals sharing code in real time. Normally it has 2 screens, i coding for coding and the other for visuals. 2 mobile phones, with an app with all the information about mobile phones (orientation, apps, etc). 
- Online algorithmic video performance: project Metonimia del cuerpo 
- Body algortihms: project cinestesia. Using a nano arduino with conductive fabrics. Exploracion de movimientos con artefactos robóticos. 
- Emodying memes small raspberry: pi zw has wifi and can connect a camera 

## Hands-on experimentation: Prototype your wearable and experiment with your training model.

I joined forces with Jorge to develop a glove as a soft sensor prototype. We used Velostat as the main material. Velostat is a variable resistor that lets electricity flow through a system or not, functioning similarly to a potentiometer. It allows modulation of how electricity flows within a circuit.

[Insert Photossssssss Here]

We designed this glove to measure the pressure an artist might apply to a material, such as clay. We sewed the neoprene to create a firm and consistent glove. Then, we connected the glove to an OSC (Open Sound Control) to receive the input and to be able to train the model. The glove sends data each time it touches the material, allowing for precise measurement of pressure.

C:\Users\vani\MDEF\mdef-template\docs\images\digitalprototyping.png

As an experiment, we trained the model to recognize a "surprised" face when the material is touched, adding an element of interaction and feedback to the process.

C:\Users\vani\MDEF\mdef-template\docs\images\surpriseproject.jpg
FOTOS con sophie con wekinator

Developing the soft sensor glove showcased the versatility of soft robotics in creative applications. It demonstrated how responsive simple materials can be used to capture intricate details of artistic processes. This project has motivated me to delve deeper into the field of soft robotics and explore its diverse applications in both art and other domains.

## Extra personal notes: 
FaceOSC x Wekinator_
Configuration: 
8338
66 xy -> 132
OSC message /raw
output: 1
IP can be the addres of your barduino or localholst

About the answers:
1 message answer
- We are going to train wekinator if we are in 1 move to 0. 
- We can also train 3 different emotions (1,2,3)
2 message answer
- We can also say while x =0 and y=1, then Z, while x=1 and y =1 then W
- Type *custom* > configure> osc message> /cara > with> integer (which means 2 answers)


# Module 5: Extending the body 
This module challenged us to create visuals to experience our trained model.

First, I explored Wekinator and its possibilities. Then, we also got to know MAX.
{Insert Photo}

In the end, I realized that I felt much more comfortable using TouchDesigner with Mediapipe for extending the body. I was already in the process of understanding the model and how to make TouchDesigner work. It was a very fun process to play with this hand-tracking recognition. It recognized each part of my fingers, so I managed to set the direction of the resized photo from the tip of my ring finger.

[Gif that shows TD](../images/gifs/Recording2024-06-21025643-ezgif.com-video-to-gif-converter.gif)






