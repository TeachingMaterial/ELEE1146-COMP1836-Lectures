---
title: DOCUMENT TITLE
description: DESCRIPTION OF DOCUMENT
class: gaia
_class:
  - lead
  - invert
style: |
    #img-right{
      float: right;
    }
     img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
    table {
      border-collapse: collapse;
      font-size: 22px;
    }
    table, th,tr, td {
      border: none!important;
      vertical-align: middle;
    }
size: 16:9
paginate: true
_paginate: false
marp: true
math: true
---

# Introduction to Android Studio

    Course Code: ELEE1146 and COMP1836

    Course Name: Mobile Applications for Engineers/Technologists

    Credits: 20

    Module Leader: Seb Blair BEng(H) PGCAP MIET MIHEEM FHEA

---

## Meet Android

- **Open-Source operating system**
  - The Android platform is built on a free operating system created by Android Inc. In 2005, Google obtained Android Inc.
  - No company or individual defines the features or direction of the development. Organizations and developers can extract, modify and use the code for creating any app
  - Phone manufacturers do not pay license fees for the operating system

- **Open Handset Alliance led by Google**
  - 80 firms that develop standards for mobile devices such as Samsung, Sony, HTC, Texas Instruments, etc.

---

## Meet Android

- **Android Phone Devices**
  - Most popular are Moto X, Galaxy, Droid, Xperia, OnePlus, Nexus and HTC One
  - OS also powers tablets, netbooks, e-readers, MP4 players and  Internet TVs
- **Emulator**
  - Duplicates how the app looks and feels on a particular device

![bg right:40% 100%](./../../figures/androidexamples.png)

---

## Meet Android -Features

<div align=center>

|Feature|Description|
|---|---|
|Beautiful UI|Android OS basic screen provides a beautiful and intuitive user interface.|
|Connectivity|GSM/EDGE, IDEN, CDMA, EV-DO, UMTS, Bluetooth, Wi-Fi, LTE, NFC and WiMAX.|
|Storage|SQLite, a lightweight relational database, is used for data storage purposes.|
|Media support|H.263, H.264, MPEG-4 SP, AMR, AMR-WB, AAC, HE-AAC, AAC 5.1, MP3, MIDI, Ogg Vorbis, WAV, JPEG, PNG, GIF, and BMP.|
|Messaging|SMS and MMS|
|Web Browser| Based on the open-source WebKit layout engine, coupled with Chrome's V8 JavaScript engine supporting HTML5 and CSS3.|
|Multi-Touch|Android has native support for multi-touch which was initially made available in handsets such as the HTC Hero.|
</div>

---

## Meet Android - Features

<div align=center>

|Feature|Description|
|---|---|
|Multi-tasking |User can jump from one task to another and same time various application can run simultaneously.|
|Resizable widgets|Widgets are resizable, so users can expand them to show more content or shrink them to save space.|
|Multi-Language|Supports single direction and bi-directional text.0|
|GCM|Google Cloud Messaging (GCM) is a service that lets developers send short message data to their users on Android devices, without needing a proprietary sync solution.|
|Wi-Fi Direct|A technology that lets apps discover and pair directly, over a high-bandwidth peer-to-peer connection.|
|Android Beam|A popular NFC-based technology that lets users instantly share, just by touching two NFC-enabled phones together..|

</div>

---

## Versions

- 31 Platform Versions and 23 API levels 

<div align=center >

|Platform Version|	API Level|	VERSION_CODE|
|--|--|--|	
|Android 6.0	|23	|MARSHMALLOW|	
|Android 5.1	|22	|LOLLIPOP_MR1|	
|Android 5.0	|21	|LOLLIPOP	|
|Android 4.4W |20 |	KITKAT_WATCH 	(KitKat for Wearables Only)|
|Android 4.4	|19	|KITKAT	|
|Android 4.3	|18	|JELLY_BEAN_MR2|

</div>

---


## Programming and Environment

- **Writing Android Apps**
  - `Java` is an Object-oriented programming language patterned after the `C++` language
- **Android Studio**
  - An `integrated development environment (IDE)` for building and integrating application development tools and open-source projects. 
  - Android Studio `IDE` is exclusively dedicated to the purpose of creating Android applications
  - Includes the `Android Software Development Kit (SDK)`
  - `XML` is used to assist in the layout of the Android emulator
---

## Emulator vs Simulator

- **Simulator**
  -  is designed to create an environment that contains all of the software variables and configurations that will exist in an app's actual production environment. 
- **Emulator**
  - attempts to mimic all of the hardware features of a production environment and software features.

**Android Emulator**
- Design, develop, prototype, and test Android apps without using a physical device
- Mimics almost every feature of a real Android handset, except placing phone calls

---

## What about Kotlin

Don't use because they wont understand the APIs' yet

---

## Getting Oriented with Market Deployment

- Platform consists of the Android OS, application development tools, and marketplace Apps are compiled into package files with an `.apk` extension
- Google Play (http://play.google.com) sells and deploys all apps
- Programs must meet minimum standards
- Apps are free or paid (If you want to charge for your app, the standard split is 70/30 between developer and wireless carrier)
- Also sold through Amazon (amazon.com/appstore) and iTunes (both charge a $99 registration fee)


---

## Opening Android Studio to Create a New Project

- We will be using the latest stable Android Studio release (June 2021) version 4.2.2
- Download and install the Android Studio from https://developer.android.com/studio/archive. 
- Make sure you have enough space on the disk, it takes 2.6GB and you would also need extra space to run it.
- **Creating the Hello World Project**
  - Open the Android Studio program
  - Create a new project, name it, supply a company domain and location

---

## Opening Android Studio to Create a New Project (cont’d)

<div align=center>

![w:900 center](../../figures/createProject1.png)

</div>

---

## Opening Android Studio to Create a New Project (cont’d)

![w:900 center](../../figures/selectDefaultActivity.png)

---

## Opening Android Studio to Create a New Project (cont’d)

![w:800 center](../../figures/emptyActivity.png)

---

## Opening Android Studio to Create a New Project (cont’d)

![w:1000 center](../../figures/projectView.png)

---

## Building the User Interface

- **Must** be intuitive
- Interface **must** not distract from functionality
- Java code or XML layout files are needed 
  - Can design interface without writing large amounts of code

---

## Taking a Tour of the Android Project View


- **Java folder** – contains Java source code
- **Res folder** – contains images, music, and video
- **Manifests folder** – contains the `Android Manifest.xml`, which contains information about the application that Android needs to run

![bg right:45% 90%](../../figures/resourcesView.png)

---

## Designing the User Interface Layout within the Virtual Device

- **Widget** – a single element on the screen (Button, Text Box, etc.)
- **Layout** – a container that holds as many widgets as needed
- **Properties pane** – contains the properties of the currently active app project or object 
- **Android Virtual Device (AVD)** – Android Studio displays an emulator configuration for design and layout purposes

---

## Designing the User Interface Layout within the Virtual Device (Cont’d.)

Click AVD Manager on the menu and Create Virtual Device at the bottom of the screen 

![w:900 center](../../figures/avd.png)

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

![w:850 center](../../figures/selectingAVD.png)

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

![w:850 center](../../figures/selectingAVDImage.png)

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

![w:850 center](../../figures/selectingAVDVerification.png)

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

Step 1: Click ‘Device for Preview (D)’ button (the emulator button) directly to the right of the Palette on the `activity_main.xml` tab, and then click Nexus 6 

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

![w:950 center](../../figures/nexusSelection.png)

---
## Designing the User Interface Layout within the Virtual Device (Cont’d.)

Step 2: Click on the text in the middle to display the Attributes window 


![w:850 center](../../figures/mainActivityView.png)

---

## Modifying the Text in the TextView Control


- Step 1: In the Android project view, click the expand arrow for the  values subfolder in the res folder to expand the folder’s contents

- Double-click the strings.xml file to display the strings.xml tab in the Project window

![w:850 center](../../figures/stringsXML.png)

---

## Modifying the Text in the TextView Control

- Step 2: Tap or click the Open editor link on the right side of the Project window to display the Translations Editor tab

- Click on the `+` button on the upper left corner of the Translations Editor

![w:800 center](../../figures/translationEditor.png)

---

## Modifying the Text in the TextView Control

A dialog box will appear. In the Key: text box type `hello` and in the Default Value: textbox, type in `Hello` followed by `your name`

![center](../../figures/addKey.png)

---
## Modifying the Text in the TextView Control

Now your Translations Editor and strings.xml file looks like this:

![center](../../figures/translationEditorAndStringsXML.png)

---

## Modifying the Text in the TextView Control

Step 4: Now click on activity_main.xml tab and then on Hello World the text property in the Attributes window and then the vertical bar next to the text property   

![w:850 center](../../figures/attributeWindow.png)

---

## Modifying the Text in the TextView Control

![w:700 center](../../figures/resourcePicker.png)

---

## Testing the Application in the Emulator

- Step 1:  Tap or click the Run ‘app’ button on the toolbar 
- Step 2: After you have run the app once and have started the emulator, next time around the Run ‘app’ button has changed

![bg right:50% 60%](../../figures/Emulator.png)