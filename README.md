# UniLWP.Droid (Free Version) UPM Package

![](Documentation~/unity-banner.jpg)

UniLWP.Droid is an Android live wallpaper framework for Unity. With it, you can create Android Studio projects that compile to live wallpaper apps. This is the free version of it (full version on: [Asset Store](http://u3d.as/1QVw)), which only contains necessary code for live wallpaper service itself.  
For packaging purposes, the plugin is uploaded as an aar file. The java source can be found on the [JavaSource](https://github.com/JustinFincher/UniLWP.Droid.Free.JavaSource) repo.

# Screenshots
| Editor             | Activity             |  Service |
:-------------------------:|:-------------------------:|:-------------------------:
![](Documentation~/unity-editor.jpg)  | ![](Documentation~/unity-activity.jpg)  |  ![](Documentation~/unity-service.jpg)

# Requirements

- Unity 2019.3+ 
- Android API: 7.0 and up
- Works best with OpenGL ES 3.0 (Vulkan is fine, but not that good)

# Installation Guide

- Add this line to your package.json
```
"dependencies": {
    "com.justzht.unilwp.droid.free": "https://github.com/JustinFincher/UniLWP.Droid.Package.Free.git" // this line
}
```
- If you are not in Android target, switch to Android target now
- Modify your build settings
  - Android API to 7.0 and up
  - Disable the Optimized Frame Pacing option
  - Disable Unity Audio (Optional)
  - Graphics API to OpenGL ES 3.0 (Optional)
- Build an apk and install it to your Android device
- Now you have one activity on your launcher, and one service if you open the live wallpaper picker

# How does UniLWP.Droid work?

# Feature Comparsion
This is the free & open-sourced version of UniLWP.Droid, and certain features are missing. For a comparsion, see the table below:
