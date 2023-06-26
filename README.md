
# VisionSurf Project Description

VisionSurf is an Android eye-controlled screen interaction utility tool for people with mobility-related injuries as well as casual smartphone users. The current demonstration shows an eye-controlled dot interacting with two established boxes to scroll the screen. This is my 2023 Capstone Project for Fairleigh Dickinson University.

---

## Defunct Notice

As the eye-tracking engine SeeSo SDK now requires a paid subscription, which I cannot afford, this app will not function beyond May 2023. 

***Due to SeeSo SDK licensing limitation, the source code is not allowed for distribution under VisualCamp's Terms of Services without a commercial license, which is why the source code will remain private.***

Future development of this app will not be continued unless an alternative to the eye-tracking engine is established.

---

# Demo

https://github.com/thang-h/visionsurf/assets/69886068/2cf3be1f-afa8-4f4d-8e0f-c7b5c1bfda51

# Diagrams

Current VisionSurf demo's architecture diagram:

![Capstone Project Diagram](https://github.com/thang-h/visionsurf/assets/69886068/b3a84154-9e91-4253-9f95-a354a3bd0a47)

Detailed architecture diagram:

![Capstone Project Diagram 2](https://github.com/thang-h/visionsurf/assets/69886068/a43a6353-f57c-48f1-9660-c001d3bbcb71)

# Credit

Tutorials and resources consulted:

Tutorial to start developing Android app in Android Studio:
https://developer.android.com/codelabs/build-your-first-android-app#0

Engine and interface:
https://docs.seeso.io/nonversioning/quick-start/android-quick-start/
https://github.com/visualcamp/seeso-sample-android
Every images file in /res folders belongs to SeeSo SDK sample app by Visual Camp, as well as the library in /libs

Gesture Service:
https://codelabs.developers.google.com/codelabs/developing-android-a11y-service
Related to: https://github.com/googlecodelabs/android-accessibility
This resource is licensed under Apache 2.0

Foreground Service and Window:
https://www.geeksforgeeks.org/how-to-draw-over-other-apps-in-android/

Interactive boxes interface and paint:
https://www.youtube.com/playlist?list=PLQRwIPDHLeOKkI3qYpG7vRoDMGijqeSOO
https://www.youtube.com/watch?v=ta2RZVZGZEM&list=PLQRwIPDHLeOKkI3qYpG7vRoDMGijqeSOO&index=3

Other resources consulted for troubleshooting:
https://stackoverflow.com/questions/24104313/how-do-i-make-a-delay-in-java
https://stackoverflow.com/questions/35930227/why-does-runonuithread-not-work-inside-service
https://developer.android.com/reference/android/view/WindowManager.LayoutParams
