# Wantujus

<div align = "center">
<img src = "https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/4ce2ba7d-fcb0-4fc0-b305-e11faf63acf0" width = "800">
</div>

## Solution

We can see that they also provided an URL.
URL = https://wantujus.bahterasiber.my/

<div align = "center">
<img src = "https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/7dc8332c-3b60-4194-9e06-6bfdd38055c8" width = "800">
</div>

We also given a hint that we need to beat the system 10 times. So just spam it until win count = 10.
Once the win count reach 10. We can see theres nothing shown. So let's check the cookie using developer tool.


<div align = "center">
<img src = "https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/c2d675f5-98fd-4d54-b5a6-d368882dd5b3" width = "800">
</div>

We can see it is encoded with Base64. Lets decrypt it using <a href="https://gchq.github.io/CyberChef/" target="_blank">CyberChef</a> from Base64
<div align = "center">
<img src ="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/040f0e5b-7df9-46cc-a13e-f8566ee66a65">
</div>

Now we get the flag 

# Flag
3108{biskut_marie}
