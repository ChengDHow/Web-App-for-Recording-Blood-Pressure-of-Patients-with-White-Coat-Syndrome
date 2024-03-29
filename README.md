# Web App for Recording Blood Pressure of Patients with White-Coat Syndrome

## About
The codes and assets in this repository are used for BN3101 project in NUS for AY22/23 Semester 1 in collaboration with clinicians from polyclinics.

## Contents
- [Getting started](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#getting-started)
- [Web app](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#web-app)
  - [Layout and structure (HTML)](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#layout-and-structure-html)
  - [Functionality (Javascript)](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#functionality-javascript)
  - [Design (CSS)](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#design-css)
- [Citations](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#citations)
- [License](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#license)
- [Author](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome#author)

## Getting Started
Install tesseract.js and node.js before running the codes.
Install node.js from: https://nodejs.org/en/download/
After installing node.js, install tesseract by entering the following command into the terminal
  npm install tesseract.js

## Web app

### Layout and structure (HTML)
**`homepage.html`** is the homepage of the application where the user is supposed to land after opening the web app. From there, the user can either select the alarm feature to set an alarm for them to take their blood pressure or record their blood pressure by taking a photo of the blood pressure machine readout screen, leading them to the pages **`alarm.html`** and **`image_recognition.html`** respectively.

### Functionality (Javascript)
Stored in the **scripts** folder are the javascript codes that performs the function of the app, including the alarm feature (**`alarm.js`**), image recognition feature and recording of input data into the user-specified google sheet (**`Capture photo from camera.js`** and **`readimage.js`**).

An open sourced optical character recognition (OCR) software, [Tesseract](https://github.com/tesseract-ocr/tesseract) was used to achieve the image recognition ability of this web app. However, its functionality is limited to specific fonts and formats.

### Design (CSS)
The color and formatting of each page are customized to be similar with minor changes to adapt to their respective usages. 

## Citations
- The image recognition function of the app was completed with reference to the script written by https://github.com/Mondal10/image-scanner
- The alarm function of the app was completed with reference to the script written by https://github.com/javascriptacademy-stash/clock-alarm/blob/master/index.js
- Please follow the guide from https://github.com/MusabDev/save-html-form-to-google-sheets to set up your google spreadsheet and enter your script link into the image_recognition.html code

## License
View full license [here](https://github.com/ChengDHow/Web-App-for-Recording-Blood-Pressure-of-Patients-with-White-Coat-Syndrome/blob/main/LICENSE.md)

## Author
CHENG Teh How (https://github.com/ChengDHow)
