## XYZReader

XYZReader is a short story reading app that was redesigned by me as part of the Udacity Android Developer course following Google’s Material Design guidlines. This includes consistent and meaningful use of Material Design UI components, fonts, color, motion and surfaces.

To get the app running just clone the repository and get the code into Android Studio.

First the user can choose a story. The main activity uses the coordinator layout with an extending toolbar:

<img src="XYZReader_Images/device-2018-04-14-223130.png" width="300">

In the detail screen the user can scroll through the book. The toolbar is colored in relation to the primary color of the image. The up button floats out of the screen at a certain scrolling point. The activity uses parallax scrolling:

<img src="XYZReader_Images/device-2018-04-14-223541.png" width="300">
