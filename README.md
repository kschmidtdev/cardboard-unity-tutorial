# cardboard-unity-tutorial
A tutorial for getting a Google Cardboard Unity3D project up-and-running.

1. [Install Unity](http://unity3d.com/get-unity/download?ref=personal)
2. [Download the Google Cardboard Unity SDK](https://developers.google.com/cardboard/unity/download)

Create a test scene instructions:

1. Run Unity
2. New Project
3. Leave as 3D
4. File->Save Scene - Save as MainScene
5. Delete the main camera
6. File->Build Settings
7. Click Android
8. Click Switch Platform
9. Click Add Open Scenes
10. Close the Build Settings Window
11. In Finder, open CardboardSDKForUnity.unitypackage in your Downloads folder
12. Click Import
13. Click on the Project tab in Unity
14. Go to Cardboard->Prefabs
15. Drag CardboardMain.prefab into the ‘Hierarchy’ section
16. Switch to the “Scene” tab
17. Zoom in and out with the mouse wheel
18. GameObject->3D Object->Cube
19. Set the cube to 0,-0.8,2.4
20. GameObject->3D Object->Plane
21. Set the plane to 0,-1.26,0
22. GameObject->Light->Point Light
23. Set to 0,1.92, 0
24. Press the Play button, and hold ALT+move the mouse around to look around
25. File->Build and Run with an Android device connected to run on device
