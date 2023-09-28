# CustomToastTutorial
In this Tutorial you will learn how to create a Custom Toast Image , when clicking a button or activating a toast.
---
---

# Starting Out!

When starting out , you will need to firsly install Android Studio , and once that has been taken care of your able to start creating your custom toast!
After Android Studio is installed start it up , and create a new project and the image below will help , select the Empty Views Activity.

<img src="https://github.com/ParkerMatthews/CustomToastTutorial/blob/main/img/pickinglayout.PNG" height="500px"
 width="2000px">

# Selecting Settings
After that select the following settings and the attached screen shot is there for help.

<img src="https://github.com/ParkerMatthews/CustomToastTutorial/blob/main/img/pickingsettings.PNG" height="500px"
 width="2000px">

- Name : CustomToast
+ Package Name : com.LOCATION.customtoast
* Save Location : C:\Users\StormTroopers\Desktop\CustomToast
* Langauge: Java
* Minimum SDK: API 21: Android 5.0 (Lollipop)

# Installing CheckMark Image


[Download Check PNG](https://github.com/ParkerMatthews/CustomToastTutorial/blob/main/img/tick.png)

Now , you can make this image anything you like but for this tutorial im going to be using a checkmark image.
Download the image , and then copy and paste it in the drawable-v24 folder , along with other two ic_launcher files that should already be in there.

<img src="https://github.com/ParkerMatthews/CustomToastTutorial/blob/main/img/locationofcheckmark.PNG" height="500px"
 width="500px">

# Starting The Code!

Firstly , you need to go into your activty_main.xml file and change the layout from <android.constraintlayout.widget.ConstraintLayout> to <Linear layout> .

