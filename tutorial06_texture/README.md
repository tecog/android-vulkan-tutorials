Tutorial 6 - Texture
=============================
Render a textured triangle


Description
----------
*  adding texture to triangle


Requirement
--------------
Pre-build shaderc with:
```
 mkdir -p  app/src/main/cpp/shaderc
 cd app/src/main/cpp/shaderc
 ${ndk_dir}/ndk-build NDK_PROJECT_PATH=. APP_BUILD_SCRIPT=${ANDROID_NDK}/sources/third_party/shaderc/Android.mk APP_STL:=${ANDROID_STL} APP_ABI:=all APP_PLATFORM:=${your-minSdkLevel} libshaderc_combined
```
Screenshot
------------
<img src="./Tutorial_6_Screenshot.png" height="400px">

```sh
~/Android/Sdk/ndk/25.1.8937393/ndk-build NDK_PROJECT_PATH=. APP_BUILD_SCRIPT=~/Android/Sdk/ndk/25.1.8937393/sources/third_party/shaderc/Android.mk APP_STL:=c++_static APP_ABI:="arm64-v8a x86_64" APP_PLATFORM:=33 libshaderc_combined
```
