# cedarvalleyvrcamp #
Course material, projects undertaken by high school students at Cedar Valley for a 2 week VR bootcamp

*still under development. 

Update 2022, a lot of this is outdated, I might have to check to see if any of these projects work on the latest version of Unity. If so, GREAT! This is a great resource for teaching children (and adults too) about the wee basics of Unity, without any code!

## Course material ##
  * ### Unity scene development ###
  * ### Sample projects ###
  * ### VR Deployment  ###

### Unity Scene development ###
  * ### Getting started ###
     Follow the download and installation instructions [here](https://unity3d.com/get-unity/download)
  * Components of a Unity project
     
  * GameObject primitives
  * Unity Asset Store GameObjects
  * GameObjects from other marketplaces
  * Materials and Textures
  * Terrain
  * Object hierarchy
  
### Sample projects ###
  * [a simple outdoor scene](https://github.com/saayv1/simple_outdoor_scene_unity)
  * [art museum](https://github.com/saayv1/art_museum)
  * [solar system](https://github.com/saayv1/solar_system)
  * [treasure hunt](https://github.com/saayv1/treasure_island_unity)
  * [treasure hunt VR](https://github.com/saayv1/treasure_island_vr)
  * [destroy objects using raycasting VR](https://github.com/saayv1/raycast_object_destroy)
  
### VR deployment ###
  * Google cardboard
     * Make sure that the Android Build Support component is selected during installation.
     ![alt text](https://github.com/saayv1/cedarvalleyvrcamp/blob/master/installer-android-build-support.png "Install android")
     * Download and install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Android Studio](https://developer.android.com/studio/install)
     * In your unity project,
      * Select File > Build Settings.
      * Select Android and click Switch Platform.
      * In the Build Settings window, click Player Settings.
      * Change the minimum build API to Android 4.4.
     
  * Samsung Gear VR
      * Make sure that the Android Build Support component is selected during installation. ![alt text](https://github.com/saayv1/cedarvalleyvrcamp/blob/master/installer-android-build-support.png "Install android")
     * Download and install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Android Studio](https://developer.android.com/studio/install)
     * In your unity project,
      * Select File > Build Settings.
      * Select Android and click Switch Platform.
      * In the Build Settings window, click Player Settings.
      * Change the minimum build API to Android 4.4.
      ![alt text](https://github.com/saayv1/cedarvalleyvrcamp/blob/master/build_setting.png "change the component setting")
