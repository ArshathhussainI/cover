# Ex.06 Book Front Cover Page Design
## Date:4-12-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Young Wizard Book Cover</title>
    <style>
    .cover-container {
      position: relative;
      width: 400px;
      height: 600px;
      margin: 0 auto;
      color: rgb(67, 150, 199);
      font-family: 'Georgia', serif;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
        }
    
    .cover-image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      filter: brightness(1.3); /* Increase brightness */
    }

    .name-text {
      position: absolute;
      bottom: 20px; /* Space from the bottom */
      left: 50%;
      transform: translateX(-50%); /* Center the text horizontally */
      font-size: 1.8em; /* Adjust font size */
      font-weight: bold;
      color: rgb(231, 236, 238);
      font-family: 'Courier New', monospace;
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7); /* Shadow for visibility */
      white-space: nowrap; /* Prevent the text from wrapping to a new line */
    }

    .main-title {
      position: absolute;
      bottom: 120px;
      width: 100%;
      text-align: center;
      font-size: 2.8em;
      font-weight: bold;
      color: orangered; /* Vibrant orange-red color for main title */
      letter-spacing: 3px;
      text-shadow: 0px 0px 12px rgba(255, 69, 0, 0.8), 2px 2px 6px black;
      font-family: 'Palatino', serif;
    }
    .series-title {
      position: absolute;
      bottom: 80px;
      width: 100%;
      text-align: center;
      font-size: 1.2em;
      color: rgb(235, 225, 225);
      font-style: italic;
      letter-spacing: 1px;
      text-shadow: 1px 1px 4px rgb(10, 234, 6);
    }
    .creator-name {
      position: absolute;
      bottom: 40px;
      width: 100%;
      text-align: center;
      font-size: 1.1em;
      color: rgb(111, 106, 106);
      font-weight: bold;
      font-family: 'Courier New', monospace;
      letter-spacing: 1px;
      text-shadow: 1px 1px 4px rgb(120, 168, 234);
    }
    </style>
    </head>
    <body>
    <div class="cover-container">
    <img src="cover.jpg" alt="Book Cover" class="cover-image">
    <div class="main-title">THE YOUNG<br>WIZARD</div>
    <div class="series-title">Mystic Fire Saga</div>
    <div class="name-text">Arshathhussain</div> <!-- Your name in a single line at the bottom -->
    </div>
    </body>
    </html>

## OUTPUT:
![alt text](<myproject/myapp/static/Screenshot (1).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
