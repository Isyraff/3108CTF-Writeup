# Johan
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/110c99f3-2f1e-4310-9e81-392bdd495d23" width = "800" >
</div>

Download the packet capture file and analyze it using Wireshark.

## Solution
We can see from the question given that the keyword is Johan went to a website and registered. Firstly,
we filter by HTTP.

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/f867aba9-e3cf-4bfa-bfa6-a892220c09c1" width = "700" >
</div>

Once filtered the packet, we can see the HTTP POST to newuser.php. Click the packet to analyze further.
We can see the input by Johan to the website but the input is in a binary number.

<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/f7cd4d52-b4c5-4ad5-b9a6-029b256c0804" width = "800" >
</div>


Combine the binary number and convert the binary number, we will get this link:
https://sites.google.comsites.google.com/view/ku4l4-lumpur/home 
We can see the given URL is unorganized. So the URL won't work.

After we fixed it, https://sites.google.com/view/ku4l4-lumpur/home.
Then we can see the page.
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/6fe2a1d5-3f55-498c-af7f-e608b8b5ce0e" width = "800" >
</div>

Scroll down, you will see a picture with a flag on it.
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/bde4e910-06d2-43b8-be9e-e565b62f28b7" width = "500" >
</div>



## Flag
3108{KU4L4_LUMPUR}

