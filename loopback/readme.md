# loopback
<p align="center">
<img src="loopback.png"/>
</p>

## Walkthrough
It's a pcap file so the first obvious thing to do was wireshark
I directly followed the tcp stream and saved the raw data to a file.

<p align="center">
<img src="1.png"/>
</p>

I then tried to modify the file.
I deleted the "Hello server!" line from it.

<p align="center">
<img src="2.png"/>
</p>

And hop ! now i have an image.
<p align="center">
<img src="file"/>
</p>

I opened the image and read the flag.
But it wasn't in the right form.
Seeing the strings of the pcapng file i found the flag format
<p align="center">
<img src="3.png"/>
</p>

## Flag
B00t2root{am_the_1}

