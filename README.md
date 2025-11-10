# Ex09 Event Registration Web Application
## Date:10/11/2025

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

```
## PAGE 1

## HTML:

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
<div class="iphone-16-pro-max-1-1">
<img src="images/page1-1-2.png" class="page1-1-2" alt="page1-1" />
<div class="rectangle-1-3"></div>
<div class="rectangle-2-4"></div>
<p class="text-5"><span class="text-black">SPORTS EVENTS
</span></p>
<p class="text-6"><span class="text-black">REGISTER
</span></p>
<img src="images/images-1-7.png" class="images-1-7" alt="images-1" />
</div>

</body>
</html>

## CSS:


/* Add font files for Irish Grover */
@font-face {
  font-family: 'Irish Grover';
  src: url('fonts/irish-grover.woff2') format('woff2'),
       url('fonts/irish-grover.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --font-family-inter: 'Inter', sans-serif;
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

.page1-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(183, 51, 51, 1);
}

.rectangle-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(30, 37, 187, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.images-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.iphone-16-pro-max-1-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-max-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-max-1-1 {
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
```
## PAGE 2

## HTML :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-max-2-1">
<img src="images/page2-1-2.png" class="page2-1-2" alt="page2-1" />
<div class="rectangle-4-3"></div>
<p class="text-4"><span class="text-black">USERNAME :</span></p>
<div class="rectangle-5-5"></div>
<p class="text-6"><span class="text-black">PASSWORD</span></p>
<p class="text-7"><span class="text-black">:</span></p>
<div class="rectangle-6-8"></div>
<p class="text-9"><span class="text-black">LOG IN</span></p>
<div class="rectangle-7-10"></div>
<p class="text-11"><span class="text-black">REMEMBER ME</span></p>
<p class="text-12"><span class="text-rgb-179-181-34">FORGOT PASSWORD ?</span></p>
<img src="images/line-1-13.svg" class="line-1-13" alt="line-1" />
<p class="text-14"><span class="text-rgb-44-199-67">CREATE AN ACCOUNT</span></p>
<img src="images/rectangle-3-15.svg" class="rectangle-3-15" alt="rectangle-3" />
<p class="text-16"><span class="text-black">LOG IN</span></p>
<img src="images/images-2-17.png" class="images-2-17" alt="images-2" />
</div>

</body>
</html>

## CSS :

/* Add font files for Itim */
@font-face {
  font-family: 'Itim';
  src: url('fonts/itim.woff2') format('woff2'),
       url('fonts/itim.woff') format('woff');
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
  --font-family-itim: 'Itim', sans-serif;
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-179-181-34: rgba(179, 181, 34, 1);
  --text-rgb-44-199-67: rgba(44, 199, 67, 1);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-179-181-34 {
  color: var(--text-rgb-179-181-34);
}

.text-rgb-44-199-67 {
  color: var(--text-rgb-44-199-67);
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

.page2-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-4-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(65, 36, 147, 1);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-5-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-6-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(179, 181, 34, 1);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-7-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 13, 13, 1);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-179-181-34);
}

.line-1-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(185, 33, 124, 1);
  border: none;
  outline: none;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-44-199-67);
}

.rectangle-3-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(101, 86, 36, 1);
  border: none;
  outline: none;
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.images-2-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.iphone-16-pro-max-2-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-max-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-max-2-1 {
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
```
## PAGE 3

## HTML :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-max-3-1">
<img src="images/page-3-1-2.png" class="page-3-1-2" alt="page-3-1" />
<div class="rectangle-15-3"></div>
<div class="rectangle-10-4"></div>
<p class="text-5"><span class="text-black">CRICKET</span></p>
<div class="rectangle-14-6"></div>
<p class="text-7"><span class="text-black">ATHLETICS</span></p>
<div class="rectangle-11-8"></div>
<p class="text-9"><span class="text-black">FOOTBALL
</span></p>
<div class="rectangle-13-10"></div>
<p class="text-11"><span class="text-black">HOCKEY</span></p>
<div class="rectangle-12-12"></div>
<p class="text-13"><span class="text-black">TENNIS</span></p>
<img src="images/images-3-14.png" class="images-3-14" alt="images-3" />
<div class="rectangle-9-15"></div>
<p class="text-16"><span class="text-black">EVENTS</span></p>
</div>

</body>
</html>

## CSS :

/* Add font files for Itim */
@font-face {
  font-family: 'Itim';
  src: url('fonts/itim.woff2') format('woff2'),
       url('fonts/itim.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-itim: 'Itim', sans-serif;
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

.page-3-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-15-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-10-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(48, 96, 61, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-14-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(135, 27, 27, 1);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-11-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(173, 33, 33, 1);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-13-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(144, 28, 86, 1);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-12-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(11, 196, 134, 1);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.images-3-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-9-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(135, 15, 15, 1);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-itim);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-pro-max-3-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-max-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-max-3-1 {
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
```
## PAGE 4

## HTML :

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-max-4-1">
<img src="images/page-4-1-2.png" class="page-4-1-2" alt="page-4-1" />
<img src="images/images-4-3.png" class="images-4-3" alt="images-4" />
</div>

</body>
</html>

## CSS : 

:root {
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

.page-4-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.images-4-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.iphone-16-pro-max-4-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-max-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-max-4-1 {
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

CLICK HERE TO VIEW PROTOTYPE : https://www.figma.com/proto/NCLlbXHuCVojlYin6yqdQ5/Untitled?node-id=44-12&t=4F7QroYDtuAJQDjp-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1


![alt text](<Screenshot 2025-11-10 221039.png>)

![alt text](<Screenshot 2025-11-10 220738.png>)

![alt text](<Screenshot 2025-11-10 220755.png>)

![alt text](<Screenshot 2025-11-10 220808.png>)

![alt text](<Screenshot 2025-11-10 220821.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
