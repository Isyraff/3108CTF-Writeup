# Lemah 

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/aafa1c10-bc15-4420-9d76-a3f23f5e2e05" width = "800" >
</div>

## Solution
Link Given: https://lemah.bahterasiber.my/

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/31844b98-ca16-4fd6-958b-f71b947f77ec" width = "600" >
</div>


We given a simple login form page. Tried simple login by using admin for both username and password nothing happened.
So I tried using developer tool using F12 and check for the source file which auth.js. 

![charcode](https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/eda58222-a309-45a6-9db9-c96468dd490b)

We can see that there is the username which is Jati and the password is in the String.fromCharCode format. It responsible in converting the unicode character to string.
I used https://r12a.github.io/app-conversion/ to convert the unicode to string without running the code. 
#### P/S Remember to set "Treat the bare number as Dec code points"

## Flag
3108{p4ssw0rd_l3m4h!}

You will get this flag after converting it
