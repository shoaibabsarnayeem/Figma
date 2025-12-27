# Ex09 Event Registration Web Application
## Date:22:12:25

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
Layout 1 
[9:01 pm, 19/12/2025] Absar Sec: <!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="image" src="img/image-5.png" />
      <img class="img" src="img/image-4.png" />
      <p class="fire-free-event">Fire Free Event&nbsp;&nbsp;25 - 26</p>
      <div class="div"></div>
      <div class="text-wrapper">Login</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Register</div>
      <p class="p">Designed By : Mohamed Asad S</p>…
[9:01 pm, 19/12/2025] Asath Sec: @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
[9:01 pm, 19/12/2025] Asath Sec: .android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 971px;
  min-height: 1574px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 630px;
  left: 40px;
  width: 891px;
  height: 180px;
  background-color: #d9d9d9;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 2023px;
  left: -7381px;
  width: 922px;
  height: 239px;
}

.android-medium .image {
  position: absolute;
  top: 19px;
  left: 25px;
  width: 922px;
  height: 184px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 203px;
  left: 301px;
  width: 370px;
  height: 370px;
  aspect-ratio: 1;
}

.android-medium .fire-free-event {
  position: absolute;
  top: 672px;
  left: 52px;
  width: 895px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 885px;
  left: 240px;
  width: 492px;
  height: 173px;
  background-color: #3540d7;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 907px;
  left: 380px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 1149px;
  left: 164px;
  width: 608px;
  height: 180px;
  background-color: #3540d7;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1182px;
  left: 296px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .p {
  position: absolute;
  top: 1420px;
  left: 56px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 60px;
  letter-spacing: -1.20px;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1493px;
  left: 412px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 60px;
  letter-spacing: -1.20px;
  line-height: normal;
}

Layout 2
[9:01 pm, 19/12/2025] Asath Sec: <!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <div class="text-wrapper">Free Fire Events</div>
      <p class="room-match-room">
        Room Match 2v2<br />Room Match 4v4<br />Room Match 6v6<br />Craftland Map<br />One Tap Match<br />Team Death
        Match<br />Zombie Hunt<br />Gun King
      </p>
      <img class="image" src="img/image-6.png" />
      <img class="img" src="img/image-7.png" />
    </div>
  </body>
</html>
[9:01 pm, 19/12/2025] Asath Sec: @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
[9:01 pm, 19/12/2025] Asath Sec: .android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 1025px;
  min-height: 1608px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 40px;
  left: 40px;
  width: 942px;
  height: 173px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 78px;
  left: 190px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .room-match-room {
  position: absolute;
  top: 258px;
  left: 57px;
  width: 925px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .image {
  top: 1159px;
  left: 591px;
  width: 340px;
  height: 400px;
  aspect-ratio: 0.85;
  position: absolute;
  object-fit: cover;
}

.android-medium .img {
  top: 1295px;
  left: 81px;
  width: 463px;
  height: 243px;
  aspect-ratio: 1.9;
  position: absolute;
  object-fit: cover;
}
layout 3
[9:02 pm, 19/12/2025] Asath Sec: <!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <div class="text-wrapper">Event Registration form</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-2">Gender</div>
      <div class="text-wrapper-3">Age</div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-4">Ful…
[9:02 pm, 19/12/2025] Asath Sec: @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
[9:02 pm, 19/12/2025] Asath Sec: .android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 1025px;
  min-height: 1608px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 64px;
  left: 22px;
  width: 975px;
  height: 224px;
  background-color: #db4b4b;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 130px;
  left: 73px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 347px;
  left: 37px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 726px;
  left: 46px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 1443px;
  left: 46px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 1288px;
  left: 46px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 1106px;
  left: 46px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1131px;
  left: 381px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1288px;
  left: 445px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 924px;
  left: 37px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 529px;
  left: 46px;
  width: 951px;
  height: 122px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 360px;
  left: 337px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  top: 541px;
  position: absolute;
  left: 334px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 733px;
  left: 235px;
  width: 574px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 937px;
  left: 320px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  top: 1456px;
  position: absolute;
  left: 334px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 80px;
  letter-spacing: -1.60px;
  line-height: normal;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-12-22 144926.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
