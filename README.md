# Ex09 Event Registration Web Application
## Date:13.11.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
HOME PAGE:
```
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-1-1">
<img src="images/node-2.png" class="node-2" alt="screenshot-2025-11-01-143954-1" />
<img src="images/node-3.png" class="node-3" alt="screenshot-2025-11-01-150614-1" />
<p class="text-4">Melody Clash-2025</p>
<p class="text-5"><span class="text-rgb-245-245-245">“Music connects hearts”</span></p>
<div class="rectangle-1-6"></div>
<p class="text-7"><span class="text-black">REGISTER</span></p>
</div>

</body>
</html>

CSS
:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-rgb-245-245-245: rgba(245, 245, 245, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-245-245-245 {
  color: var(--text-rgb-245-245-245);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 10px;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(237, 99, 99, 1);
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 1);
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 16px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-245-245-245);
}

.rectangle-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(241, 178, 75, 1);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
  opacity: 0.8999999761581421;
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-pro-1-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}
```
EVENT PAGE
```
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-2-1">
<img src="images/node-2.png" class="node-2" alt="screenshot-2025-11-01-144119-1" />
<p class="text-3"><span class="text-black">Musical</span></p>
<p class="text-4"><span class="text-black">Events</span></p>
<p class="text-5"><span class="text-black">1.solo singing
2.Duet Battles
3.Musical Instrument
4.Theme Rounds
5.Genre Challenge</span></p>
</div>

</body>
</html>

CSS

/* Add font files for Jacquard 24 */
@font-face {
  font-family: 'Jacquard 24';
  src: url('fonts/jacquard-24.woff2') format('woff2'),
       url('fonts/jacquard-24.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Jaini Purva */
@font-face {
  font-family: 'Jaini Purva';
  src: url('fonts/jaini-purva.woff2') format('woff2'),
       url('fonts/jaini-purva.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jacquard-24: 'Jacquard 24', sans-serif;
  --font-family-jaini-purva: 'Jaini Purva', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jacquard-24);
  font-weight: normal;
  font-size: 48px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jacquard-24);
  font-weight: normal;
  font-size: 48px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jaini-purva);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-pro-2-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
REGISTRATION PAGE
```
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-3-1">
<img src="images/node-2.png" class="node-2" alt="screenshot-2025-11-01-144530-1" />
<p class="text-3"><span class="text-white">
REGISTRATION</span></p>
<p class="text-4"><span class="text-white">EVENT</span></p>
<div class="rectangle-4-5"></div>
<div class="rectangle-5-6"></div>
<div class="rectangle-6-7"></div>
<div class="rectangle-7-8"></div>
<div class="rectangle-8-9"></div>
<p class="text-10"><span class="text-black">NAME</span></p>
<p class="text-11"><span class="text-black">DEPARTMENT</span></p>
<p class="text-12"><span class="text-black">PHONE NUMBER</span></p>
<p class="text-13"><span class="text-black">EVENT</span></p>
<p class="text-14"><span class="text-black">EMAIL</span></p>
<div class="rectangle-9-15"></div>
<p class="text-16"><span class="text-rgb-245-245-245">SUBMIT</span></p>
</div>

</body>
</html>

CSS

/* Add font files for jsMath-cmr10 */
@font-face {
  font-family: 'jsMath-cmr10';
  src: url('fonts/jsmath-cmr10.woff2') format('woff2'),
       url('fonts/jsmath-cmr10.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Kings */
@font-face {
  font-family: 'Kings';
  src: url('fonts/kings.woff2') format('woff2'),
       url('fonts/kings.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Irish Grover */
@font-face {
  font-family: 'Irish Grover';
  src: url('fonts/irish-grover.woff2') format('woff2'),
       url('fonts/irish-grover.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jsmath-cmr10: 'jsMath-cmr10', sans-serif;
  --font-family-kings: 'Kings', sans-serif;
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-245-245-245: rgba(245, 245, 245, 1);
}

.text-white {
  color: var(--text-white);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-245-245-245 {
  color: var(--text-rgb-245-245-245);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(235, 14, 14, 1);
  font-family: var(--font-family-jsmath-cmr10);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(237, 99, 99, 1);
  font-family: var(--font-family-jsmath-cmr10);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-4-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 0.8);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
}

.rectangle-5-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
  opacity: 0.800000011920929;
}

.rectangle-6-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
  opacity: 0.800000011920929;
}

.rectangle-7-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
  opacity: 0.800000011920929;
}

.rectangle-8-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(217, 217, 217, 1);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
  opacity: 0.800000011920929;
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kings);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kings);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kings);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kings);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kings);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-9-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 10px;
  opacity: 0.8999999761581421;
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-245-245-245);
}

.iphone-16-pro-3-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
END PAGE
```

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-4-1">
<div class="node-2"></div>
<img src="images/node-3.png" class="node-3" alt="screenshot-2025-11-01-165518-1" />
<p class="text-4"><span class="text-white">The stage awaits your melody 
   Thank you for registering!
           On Melody Clash</span></p>
<p class="text-5"><span class="text-white">         Contact Us
www.melodyclash.com</span></p>
<p class="text-6"><span class="text-white">saveethaengineering@gmail.com</span></p>
</div>

</body>
</html>

CSS

/* Add font files for Kiwi Maru */
@font-face {
  font-family: 'Kiwi Maru';
  src: url('fonts/kiwi-maru.woff2') format('woff2'),
       url('fonts/kiwi-maru.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-kiwi-maru: 'Kiwi Maru', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.5;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.8999999761581421;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  border: 1px solid rgba(0, 0, 0, 0.25);
  font-family: var(--font-family-kiwi-maru);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(255, 255, 255, 1);
  font-family: var(--font-family-kiwi-maru);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(245, 245, 245, 1);
  font-family: var(--font-family-kiwi-maru);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-16-pro-4-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

## OUTPUT:

<img width="1265" height="627" alt="image" src="https://github.com/user-attachments/assets/dc3e8983-160b-49d5-8524-d4d898297a39" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
