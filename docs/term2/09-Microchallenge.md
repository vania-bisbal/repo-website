# Microchallenge: Immersive Experiences
<img src="../images/volumetricdisplay.png" alt="volumetric display" style="border-radius: 10px;"> 

For this microchallenge, Jorge and I decided to partner up to create an artifact that reflects our shared interests. We did some brainstorming about our main inqueries and interests. 
<img src="../images/brainstorming3.png" alt="final brainstorming session" style="border-radius: 10px;"> 

I've been researching by our relationship with technology and how AI might shape us in the future. However, for this microchallenge, I wanted to focus on the *physical* impact of technology use. I was inclined by the approach of technological fatigue. *Technological or digital fatigue is a widespread issue that has gained significant attention, especially in the context of increased screen time and reliance on digital devices for work, education, and socializing.* Digital fatigue manifests as a form of mental exhaustion resulting from excessive screen time, impacting productivity and well-being  

Moreover, from my personal experience, I tend to work from 12 to 14 hours a day on my laptop, and this is an increasing behavior I've been observing more frequently. Thus, I decided to explore new methods of immersive learning, working, or researching that go beyond traditional devices, even VR, because it can also lead to digital fatigue.

We created an AI hologram. It's an AI assistant for both designers and non-designers, designed to help you find inspiration for projects in a non-traditional way. Holograms, in their most basic form, are very old technology, yet their high-tech evolution is a volumetric display. On the first day, we delved into how we could utilize the space surrounding the laptop, where people regularly work, and the various methods of creating a hologram or a low-tech projector. 

<img src="../images/hologram.png" alt="hologram" style="border-radius: 10px;"> 

# For the prototype:
We learned about the Pepper's Ghost effect and various ways to prototype the display. The simplest method we found was the pyramid effect, so we decided to laser cut a first sample to see if it actually worked. We used some YouTube videos featuring the pyramid hologram effect to test its functionality.

<img src="../images/hologramdraw.jpeg" alt="hologram draw" style="border-radius: 10px;"> 
<video controls src="../images/jorgepiramid.mp4" title="first try"></video>


# For the intelligence:
Inspired by Modmatrix, we aimed to produce an AI that could generate an image from a prompt. We enhanced the experience by enabling voice commands instead of typing, allowing it to connect with Dall-e for creative inspiration or with KittyCAD for 3D modeling needs. Furthermore, we needed to achieve a four-screen video reflection for the pyramid from the AI output. It took some time, but ultimately, we managed to do it with Blender and Python. Check our repository [here](https://github.com/jmuozan/AI-generated-holograms).

C:\Users\vani\MDEF\mdef-template\docs\term1\hologram4.mp4

<!--*add images and gifs here of the build process* -->
<!-- Markdown Content -->
<div class="image-grid">
  <img src="../images/hologram1.jpeg" class="grid-item" alt="Iaac">
  <img src="../images/hologram2.jpeg" class="grid-item" alt="atelier project">
  <img src="../images/hologram33.jpeg" class="grid-item portrait-image" alt="bcn street">
  <img src="../images/hologram4.mp4" class="grid-item" alt="cnc">
  <!-- Add more images as needed -->
</div>

<!-- CSS Styles -->
<style>
  /* Styles for the image grid container */
  .image-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Two columns */
    /*grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));*/ /*use this line of code to create a responsive grid that will place all images in one continuous row - each image will shrink accordignly*/
    grid-gap: 10px;
    /* Additional grid container styles can be added here */
  }

  /* Styles for individual grid items (images) */
  .grid-item {
    width: 100%;
    height: auto;
    object-fit: cover;
    border-radius: 5px; /* Add rounded corners to images */
    /* Additional styles for grid items can be added here */
  }
  /* Styles for portrait images */ /*apply this class to any portrait photo in a grid to crop it to landscape: class="grid-item portrait-image" */
.portrait-image {
    object-position: center middle; /* Adjust this property to control the cropping of portrait images */
  }
</style>

Participating in this microchallenge was immensely enjoyable because we were deeply engaged in writing the code. I'm confident we improved our Python coding skills significantly through the use of AI tools, despite starting with limited knowledge. The coding took longer than expected, but we managed to make it work. For the pyramidal hologram prototype, I believe there is potential for further development since the displayed image was still quite small.

<img src="../images/hologram.gif" class="grid-item" alt="Jorge&vania">
