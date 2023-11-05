# Home
![limabcn](images/LimaBcn.jpg)
<!--*add images and gifs here of the build process* -->
<!-- Markdown Content -->
<div class="image-grid">
  <img src="../images/iaac.jpeg" class="grid-item" alt="Iaac">
  <img src="../images/atelier.jpeg" class="grid-item" alt="atelier project">
  <img src="../images/street.jpeg" class="grid-item portrait-image" alt="bcn street">
  <img src="../images/cnc.jpeg" class="grid-item" alt="cnc">
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
<br>
<br>
<div id="homepage">
  <h1 id="typewriter-text"></h1>
</div>
  
