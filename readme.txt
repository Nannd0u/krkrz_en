Kirikiri Z 1.4.0 


  【About Kirikiri Z】 
  Kirikiri Z is a development/execution environment for creating 2D games and applications. 


  【download page】 
  http://krkrz.github.io/ 


  【help】 
  For detailed documentation, please refer to the various online help on the above page. 
  Help is provided on the following pages. 

  Kirikiri Z Reference  http://krkrz.github.io/docs/kirikiriz/j/contents/index.html 

  TJS2 reference  http://krkrz.github.io/docs/tjs2/j/contents/index.html 

  List of changes in Kirikiri Z from Kirikiri 2  http://krkrz.github.io/updatefromkr2.html 

  Please use tools such as releasers from Kirikiri 2.  You can download it from below. 
  http://krkrz.github.io/download/kr2_232r2.zip 


  【How to make a novel game】
  Download "KAG for Kirikiri Z" from http://krkrz.github.io/  and place the extracted data folder in the same folder as his tvpwin32 / tvpwin64.exe. 
  How to use KAG3 is on the following page. 
  https://krkrz.github.io/krkr2doc/kag3doc/contents/index.html 
  There is also "KAG3 with conger eel for Kirikiri Z", which has a save/load screen and a configuration screen added to KAG3. 
  This may be easier at first. 
  Basic usage is the same. 


  【File】 
  \imageviewer : Simple image viewer.   D&D this folder to tvpwin32/tvpwin64.exe to start. 
  \movieplayer : A simple video player.   D&D this folder to tvpwin32/tvpwin64.exe to start. 
  \plugin : Contains various plugins. 
  \plugin64 : 64bit versions of various plugins are included. 
  debugger.sdp : Debugger configuration file. 
  krkrdebg.exe : Debugger itself. 
  krkrdegb_readme.txt : Debugger description. 
  license.txt : A text file containing the license text. 
  readme.txt : This file.  A brief description is provided. 
  tvpwin32.exe : Kirikiri Z body. 
  tvpwin32_dbg.exe : Kirikiri Z built with the debugger enabled. 
  tvpwin64.exe : 64bit version of Kirikiri Z. 


  [About the operation of his TJS2 script in Kirikiri 2] 
  Kirikiri Z is not fully compatible with Kirikiri 2, so some changes are required to make his TJS2 script work for Kirikiri 2. 

  In Kirikiri Z, the standard character code has been changed to UTF-8. 
  If you want to run the old script as it is, you need to add -readencoding=Shift_JIS on the command line. 

  His KAGParser and menus, which were built-in features, are now plug-ins. 
  If you need KAGParser and menu classes, you need to link KAGParser.dll and menu.dll. 

  Touch is enabled on devices with multi-touch support enabled devices. 
  (It works like onTouchDown arrives instead of onMouseDown ) 
  If touch processing is not used, it must be disabled so that it can be handled with conventional mouse processing. 
  Set Window.enableTouch to false to disable it. 

  PassThroughDrawDevice has been removed, so you'll need to rewrite where it's used. 

  If you are using other deleted methods, etc., you will need to rewrite those processes. 

  For more detailed changes, please refer to the above "List of changes from Kirikiri Z in Kirikiri 2" page. 


  【Change log】 
  2017/12/25 1.4.0.8 
  2016/08/10 1.3.3.7 
  2016/08/01 1.3.2.6 
  2016/06/03 1.3.1.5 
  2016/05/31 1.3.0.4 
  2015/08/17 1.2.0.3 
  2014/08/03 1.1.0.2 
  2013/12/31 1.0.0.1 See the history page for release details. 
 http://krkrz.github.io/olderversions.html 

 