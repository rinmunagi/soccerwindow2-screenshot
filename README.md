=========================================================

#  __SOCCERWINDOW2-SCREENSHOT__

=========================================================

## Overview  
The soccerwindow2-screenshot is made for [the spectator app.](https://github.com/rinmunagi/spectator_app)  
The Spectator App. is developed for extension to a soccer monitor that is used in RoboCup soccer simulation 2D league. 
The aim of the extension is to make the experience of watching games more entertaining.  
The soccerwindow2-screenshot is necessary for capturing the images in order for the CNN to use them.  

We modified the following original soccerwindow2. 
- [soccerwindow2](https://ja.osdn.net/projects/rctools/releases/68532/)  

## Requirement
 - Qt-3.3.x, Qt-4.3 or later
 - boost-1.32 or later
 - [librcsc-4.0.x](https://ja.osdn.net/projects/rctools/downloads/51941/librcsc-4.1.0.tar.gz/)  

## Install
```
git clone http://github.com/rinmunagi/soccerwindow2-screenshot.git
```
Enter the following commands in the soccerwindow2-screenshot directory.  
```  
./configure  
make  
su  
make install  
```  

This process generates the required binary.  
And they are installed in '/usr/local'.  

if librcsc isn't installed in the system directory, the option '--with-librcsc' is needed.  
```  
./configure --with-librcsc=/path/to/librcsc/prefix
```  

## Usage
Enter the following command to execute.  
```  
soccerwindow2 
```  

## Author
- Yudai Suzuki (Osaka Prefecture University)  
- Takuya Fukushima (Osaka Prefecture University)  
- Lea Thibout (Osaka Prefecture University)  
- Tomoharu Nakashima (Osaka Prefecture University)  
- Hidehisa Akiyama (Fukuoka University)  
