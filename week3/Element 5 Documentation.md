# Element 5 Documentation

In element 5 I made a set of meshes and a floor consisting of:
1. a cube
2. triangle
3. ellipsoid
4. capsule
5. cone
6. cylinder
 
I then arranged them with the cube and ellipsoid in the centre surounded by the other meshes and made the changed the lightings coulour and intensity to create a pink light.
I did this by simply altering the x, y and z co-ordinates of the meshes and changing the rbga value of the lighing.

[![image of code](/assets/images/meshCode.png "Code fo the meshes in my scene")]

I then made a village scene, altering the trees and placement of them by changing the image and count of them to create a more autumnal feel in the scene

[![image of code](/assets/images/VillageCode.png "Code fo the village in my scene")]
[![image of village](/assets/images/VillageScene.png "Village")]

After that I made 2 buttons that can be pressed to switch between the two scenes. This is done by importing the Scene, ArcRotateCamera, Vector3, Camera, Engine and the setSceneIndex, i then create a GuiButton then gave the button a onPointerUp which logs when its clicked and calls the setSceneIndex.
[![image of ButtonCode](/assets/images/ButtonCode.png "Buttons")]
i Then creat an ArcCamera function with a preset alpha, beta, radius and target, Then I create a MenuScene Funtion which creates a new scene using the imported engine, Makes a fullscreen gui and makes 2 buttons that both call the setSceneIndex and creates the arcRotateCamera. 
[![image of MenuSceneCode](/assets/images/MenuCode.png "Menu")]