# Tugasan 1: Seruan Perwira
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/b6df7b4f-948b-4ee8-8248-d36f12c8245e" width="700" >
</div>

This is the YouTube link: https://youtu.be/DFBNEsKJW6I

## Solution
Click the YouTube link, there will be a file to be downloaded.
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/772ffd4d-4026-4daf-bef7-88e5db94a51c" width="600" >
</div>

Extract the .zip file and there will be a .eml file named in a morse code type of format.

Open the file. I used outlook email application. The email included .zip file to be downloaded and a morse code. The content of the .zip file are encrypted where we dont have the password yet. One of it is flag.txt file which might contain the flag.
I used online morse code translator online to crack the morse code.
https://morsecode.world/international/translator.html

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/c9357407-5f02-485e-b23b-127bee056b24" width="500" >
</div>

Based on the hint given, I just try and error which is 3108, the name of CTF competition. I tried the 3108 as a password of the flag.txt. You will get the flag.

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/431960d4-915e-4b1c-b833-29e8bf62a882" width="500" >
</div>

## Flag
3108{1E2A3C68CC5C0207886EDE403EEF230DC7C0FBD0}
