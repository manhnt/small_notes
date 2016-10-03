# Setting OpenCV libraries and dependencies

If you have not build OpenCV for Visual Studio 2015, follow the guide in this link:
http://dogfeatherdesign.com/opencv-3-0-microsoft-visual-studio-2015-cmake-and-c/

## Setting OpenCV header include directories:
Right click project title -> Properties -> C/C++ -> General SEttings -> Additional Include Directories.
Add the following directory: C:\opencv\build\install\include

## Setting OpenCV library directory:
Right click project title -> Properties -> Linker -> General Settings -> Additional Library Directories.
Add the directory:C:\opencv\build\install\x64\vc14\lib

Also in the Linker settings -> Input -> Additional Dependencies,  add the following libraries:
opencv_core310.lib
opencv_highgui310.lib
opencv_imgproc310.lib
opencv_imgcodecs310.lib
opencv_video310.lib
opencv_videoio310.lib

## Setting environment PATH variable:
Add the following directory to environment PATH variable:
C:\opencv\build\install\x64\vc14\bin
C:\opencv\build\install\x64\vc14\lib