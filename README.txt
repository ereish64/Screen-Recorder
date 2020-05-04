This software in WINDOWS ONLY!

For first time setup, you will need to download the FFmpeg executable and place it in this folder.
Simply go to: https://ffmpeg.zeranoe.com/builds/
select a version (any should work), select your windows architecture (if you dont know, then choose 32-bit), under linking click static, then click download!
Now, extract the zip folder (Right click the zip file in downloads, click extract all.) This should create a new folder containing ffmpeg in the name
open the ffmpeg folder, inside there should be a folder named bin, double click this folder.
Inside the bin folder, there should be a file named ffmpeg.exe
drag ffmpeg.exe into this folder (the one containing this readme)
you are done!
we only needed the ffmpeg.exe, so you can delete the folder you just downloaded once you moved ffmpeg.exe out.


To start screen capture, simply run (or double click) capture.exe The target FPS and output filename can be set through config.cfg
When finished recording the video simply press q in the ffmpeg (command prompt) window. The program will then save the video and exit.

Thanks to FFmpeg, this program uses your GPU to ensure a fast and high quality video output!
For more information about FFmpeg includeing downloads, go to FFmpeg.org, it is open source and free!