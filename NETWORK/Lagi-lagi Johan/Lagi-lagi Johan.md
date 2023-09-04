# Lagi-lagi Johan
<div align ="center">
<img src="https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/dd9a381f-2cee-4d2d-b3ab-b7ede60219a6" width = "700" >
</div>

## Solution
We can see that we are given another packet capture file. We use Wireshark to analyze it. 
Then we try to filter the packet with HTTP.

<div align = "center">
<img src = "https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/4ca7c65a-3813-4618-98e0-9323338c6288" width = "700">
</div>

From the packets we see, there's a HTTP POST request. Inspect the packet and we can see uname and pass is our flag 
<div align = "center">
<img src = "https://github.com/Isyraff/3108CTF-Writeup/assets/107107155/53529a85-fbbb-4665-88d4-55476b5ca04d" width = "800">
</div>


## Flag
3108{P4TR10T1C}
