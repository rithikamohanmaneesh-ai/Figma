# Ex09 Event Registration Web Application
## Date:19/12/25

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
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="frame"><img class="dj-disco-music-party" src="img/dj-disco-music-party-people-22215831-1.png" /></div>
      <div class="text-wrapper">2025</div>
      <div class="div">INTERESTING QUIZ</div>
      <div class="text-wrapper-2">ATTRACTIVE</div>
      <div class="text-wrapper-3">GAMES</div>
      <div class="HOSTEL-FEST">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HOSTEL&nbsp;&nbsp; FEST</div>
    </div>
  </body>
</html>
globles.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 741.4px;
  min-height: 834.8px;
  position: relative;
}

.android-medium .frame {
  position: absolute;
  top: -35px;
  left: -37px;
  width: 853px;
  height: 853px;
  display: flex;
}

.android-medium .dj-disco-music-party {
  margin-top: 33.1px;
  width: 741.4px;
  height: 817.8px;
  margin-left: 33.8px;
  transform: rotate(-0.37deg);
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 220px;
  left: 193px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.37deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}


.android-medium .div {
  position: absolute;
  top: 319px;
  left: 280px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.37deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 408px;
  left: 345px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.37deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 485px;
  left: 420px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.37deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .HOSTEL-FEST {
  position: absolute;
  top: 160px;
  left: 66px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.37deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium"><img class="image" src="img/image-2.png" /></div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  display: flex;
}

.android-medium .image {
  width: 700px;
  height: 840px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">ENJOYMENT 100%</div>
      <div class="div">HURRY UP.......</div>
      <div class="text-wrapper-2">COME FAST .......</div>
      <div class="text-wrapper-3">MAKE YOUR MIND FREE</div>
      <div class="text-wrapper-4">DJ AVAILABLE....!!!!</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
    </div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 117px;
  left: 122px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 241px;
  left: 131px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 585px;
  left: 172px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 357px;
  left: 148px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 469px;
  left: 151px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: -0.80px;
  line-height: 56.0px;
  white-space: nowrap;
}

.android-medium .star {
  position: absolute;
  top: 80px;
  left: 566px;
  width: 74px;
  height: 20px;
}

.android-medium .img {
  position: absolute;
  top: 666px;
  left: 586px;
  width: 95px;
  height: 90px;
}

.android-medium .star-2 {
  position: absolute;
  top: 737px;
  left: 53px;
  width: 95px;
  height: 90px;
}

.android-medium .star-3 {
  position: absolute;
  top: 65px;
  left: 559px;
  width: 95px;
  height: 90px;
}

.android-medium .star-4 {
  position: absolute;
  top: 42px;
  left: 6px;
  width: 95px;
  height: 90px;
}







```
## OUTPUT:

![alt text](<Screenshot (46).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
