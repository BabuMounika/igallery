# Ex.08 Design of Interactive Image Gallery
## Date:16//11/24

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <link rel="stylesheet" href="styles.css">
  <style>
   
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  padding: 20px;
}


.gallery-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 15px;
  justify-items: center;
  padding: 20px;
}


.gallery-item {
  width: 100%;
  overflow: hidden;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}


.gallery-item img {
  width: 100%;
  height: auto;
  transition: transform 0.3s ease-in-out;
}


.gallery-item:hover img {
  transform: scale(1.05);
}



  </style>
</head>
<body>
  <div class="gallery-container">
    <div class="gallery-item">
      <img src="Beach .jpg" alt="Image 1">
    </div>
    <div class="gallery-item">
      <img src="Rain.jpg" alt="Image 2">
    </div>
    <div class="gallery-item">
      <img src="Moon.jpg" alt="Image 3">
    </div>
    
    <div class="gallery-item">
      <img src="Flower.jpg" alt="Image 4">
    </div>
    <div class="gallery-item">
        <img src="Road.jpg" alt="Image 5">
      </div>
      
  </div>
  <footer>
        Developed and designed by Mounika M</h3>
</footer>
</body>
</html>




```

## OUTPUT:
![alt text](<Screenshot (27).png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
