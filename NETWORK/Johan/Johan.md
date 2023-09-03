# Johan
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/110c99f3-2f1e-4310-9e81-392bdd495d23" width = "800" >
</div>

Download the packet capture file and analyze it using Wireshark.

## Solution
We can see from the question given that the keyword is Johan went to a website and registered. Firstly,
we filter by HTTP.


Once filtered the packet, we can see the HTTP POST to newuser.php. Click the packet to analyze further.
We can see the input by Johan to the website but the input is in a binary number. 
