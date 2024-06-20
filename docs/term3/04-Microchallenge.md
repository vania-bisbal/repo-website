## Microchallenge: Digital Twin
For this microchallenge, I wanted to learn more about TouchDesigner and explore its potential with different inputs. Over the past few months, I have been intrigued by Mediapipe and its various applications. Jorge and I were exploring its uses and its connection to craftsmanship. Although we didn't collaborate directly on this challenge, each of us focused on learning a different skill. We worked together to better understand the tool and develop some workarounds in our processes.


## Finding Inspiration in TouchDesigner
TouchDesigner artists are creating remarkable work using sensors, cameras, audio, voice, and more. It offers an immersive experience. Here are some designers using TouchDesigner:
## The Concept
An art piece digital twin...

## Mediapipe
After exploring various ways to connect Mediapipe, I discovered a method using a Mediapipe API for TouchDesigner. You can find the repo XXXX here and a YouTube tutorial. Once installed, Mediapipe can be used for pose tracking, hand tracking, object recognition, and other gesture recognitions.

## Electronic Gloves Prototype
While using Mediapipe's hand tracking, I realized that hand-tracking alone wasn't sufficient to measure the artist's effort while creating a piece. So, I decided to create a pair of electronic gloves to capture the pressure exerted on the material.

To create the gloves, I used documentation on soft robotics from Fabricademy students. I used neoprene for the glove prototype and Velostat for the circuit. I also used conductive fabric and conductive thread to test the conductivity.

When the gloves were ready, I connected them with crocodile cables to an Arduino to run the code and start receiving data. Here is the Arduino code: XXXX

Here are more resources about soft robotics I found interesting:
-
-
-

## TouchDesigner
After validating the data from the gloves, I watched some tutorials to send the serial plotter data from Arduino to TouchDesigner. Initially, I encountered some difficulties, but it was relatively easy to set up once I got the hang of it. You need to open a serial component to start receiving data from your Arduino. Ensure the data is separated by commas for easy identification. Since I had right and left gloves, I needed to isolate each data point.

With both inputs—Mediapipe hand-tracking values and the pressure from the gloves—I used some tutorials to create effects. I enjoyed the Blob Tracking and the particle rain effects. Here are some of the tutorials: XXXX

## Setup
For the final setup of the prototype, I recycled a piece of wood from my previous microchallenge. I realized it was easier and more efficient to use my mobile camera instead of the laptop one. This allowed for better placement and adaptability to different artistic practices. For example, ceramics differ from glass blowing. I used OBS Studio to control the cameras I connected to TouchDesigner. It automatically appears as an option in TouchDesigner. Additionally, I used VDO.Ninja to broadcast from my phone. You can also broadcast from anywhere in the world using a QR code. Here you can see the tutorial: XXXX

## Output Video and Experience
XXXXX video link

Learning more about TouchDesigner and diving into additional areas like soft robotics, Arduino, Python, and OBS Cam was a fascinating experience. I had a lot of fun and was deeply interested in the immersive experiences you can create by tracking or monitoring gestures, poses, and hands from a camera. There were some challenges; initially, I wanted to create a matrix for the gloves to receive more data or even measure the fingers. However, Santi suggested keeping it simple (MVP) so I could manage to make everything work. Luckily, I followed that advice and continued with simple gloves; otherwise, I would have run out of time. I am eager to continue exploring soft robotics and TouchDesigner with the Mediapipe API.

Matrix copper inspiration https://www.kobakant.at/DIY/?p=7943
https://www.youtube.com/watch?v=swTN-SDRViU

Connie AI artist
https://www.artconnect.com/connie-bakshi-XLwfXhEy2e2G4aaVEkMcl
https://www.stephaniedinkins.com/
artisan vr https://mw17.mwconf.org/glami/weaving-a-better-future-virtual-reality-app/
deezen https://www.dezeen.com/2013/11/20/honey-bees-can-be-trained-to-detect-cancer-in-ten-minutes-says-designer-susana-soares/
space plants https://www.instagram.com/p/CHu4TVyhgXX/?epik=dj0yJnU9NTU0ZGE3blZoYUF3d05NUXhJX3NMS1laSWcyakhqNDgmcD0wJm49cl82TWhjbzlqRnlqWTA0bzN3XzRWUSZ0PUFBQUFBR1k3OVp3&img_index=1
https://www.instagram.com/laragess__/
https://www.leeboroson.com/art/category/recent-projects lee boronson
everyday objects https://hotelsabovepar.com/objective-gallery/

https://www.meikeharde.com/portfolio-item/chromatographics/ chromatographics

mediapipe https://github.com/mgyong/awesome-mediapipe?tab=readme-ov-file#desktop-examples
torin mediapipe https://github.com/torinmb/mediapipe-touchdesigner/releases

https://derivative.ca/community-post/tutorial/overstim-sim-experience/68549
carme
