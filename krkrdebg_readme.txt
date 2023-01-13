Kirikiri Z/TJS2 Debugger 

●How to use 
Launch krkrdebg.exe. 
Select Settings, Project Settings. 
The full path of tvpwin32_dbg.exe attached to the execution file path 
-debug in the argument 
Full path of data in project folder ( ex. C:\krkr\debugger\data ) 
Set the execution directory to the working folder ( ex. C:\krkr\debugger ) 
Script extension is the script extension separated by a space ( ex. .tjs ) ("." is also required) 
Set above. 
TJS files are listed on the left. 
If you save the project with File → Save As, it will be easier next time. 

If there is debugger.sdp in the same directory, load that configuration file by default 
If invoked with -p filename.sdp as an argument, read that configuration file. 

If you double-click the line with the execution statement of the file that is executed toward the beginning, such as startup.tjs or Config.tjs, a breakpoint will be pasted. 
(Breakpoints can be pasted on empty lines, but they do not stop.) 

Then run it and it will stop at the breakpoint. 
You can continue execution by tracing or stepping. 

Setting breakpoints during execution does not take effect immediately. 
Stop with a break (pause) and execute again to reflect. 

Various paths are saved in the configuration file as relative paths. 


【Change log】 
2015/08/17 1.0.1.1 Replaced characters that cannot be displayed with 〓, and fixed the problem that characters cannot be displayed in UTF-8.