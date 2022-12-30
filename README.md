-------------------------------------------------------------------------------------------
VIDEO STEPS LISTED BELOW - UPDATED DEC 30, 2022*
--------------------------------------------------------------------------------------------
✅Step 1:

FILE - https://www.videohelp.com/software?d=recover_mp4_192.zip

✅Step 2:

Download ffmpeg Tool (ffmpeg-3.4.1): 

FILE for Win64 (common)  - https://www.videohelp.com/software?d=ffmpeg-3.4.1-win64-static.zip

or

FILE for Win32 (slower)  -  https://www.videohelp.com/software?d=ffmpeg-3.4.1-win32-static.zip

For Reference:
https://ffmpeg.org/download.html
https://ffmpeg.org/releases/?C=N;O=D

✅STEP 3: 

Extract ffmpeg.zip, then extract recover_mp4.zip inside /ffmpeg/bin/ directory so that all the .exe files are in the same folder!

✅STEP 4:

Copy your "good.mp4" reference file
Copy your "bad.mp4" damaged file to be repaired
into SAME directory with .exe files as described in STEP 3

✅STEP 5:

Search – then type "CMD" (without quotes) -- then right-click on COMMAND PROMPT to RUN AS ADMINISTRATOR and confirm with YES

✅STEP 6:

Change your working directory inside COMMAND PROMPT to where your ffmpeg.exe and recover_mp4.exe and .mp4 video files are (see step 3) *Make sure to add the letters "cd" before you paste your directory.

✅STEP 7:

Copy/Execute the following command inside COMMAND PROMPT + press ENTER

    recover_mp4.exe good.mp4 --analyze

✅STEP 8:
After analysis is completed, run proposed commands you receive from recover_mp4 tool, for example:

    recover_mp4.exe bad.mp4 result.h264 result.aac --lav

✅STEP 9:

Copy and Paste the second line such as:

    ffmpeg.exe -r 30 -i recovered.h264 -i recovered.aac -bsf:a aac_adtstoasc -c:v copy -c:a copy recovered.mp4

(above are only example commands for step 9, they will be different for each video format - follow instructions you receive from recover_mp4 tool!)

✅Step 10: OPEN RECOVERED VIDEO! (REMEMBER AUDIO WILL BE A SEPARATE FILE)

If the file isn't playable it might be because the file type is unsupported, the file extension is incorrect, or the file is corrupt in a way that ffmpeg is unable to decipher. Make sure you are using a reference file that is using the same format as the corrupted video.

--------------------------------------------------------------------------------------

#filerecovery #mp4 #corruptvideo
-------------------------------------------------------------------------------------

►Facebook: [@IAMZenju](https://fb.gg/IAMZenju)

►Instagram: [@IAMZenju](https://www.instagram.com/iamzenju/)

-----------------------------------------------------------------------------------------------

