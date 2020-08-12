# Writeup;

After reading the Description, I thought there will be something in firefox history as one of the authors like firefox and uses it as per the description.
But There is nothing over there and "google" is mentioned. So I've tried chromehistory and got results as follows. 

![Screenshot from 2020-08-12 01-50-28](https://user-images.githubusercontent.com/47820151/89995547-75c2b880-dc3e-11ea-8493-1c83936e9749.png)

By going to that link It's pastebin link and we see there is a file which has Malware.exe in it.
As the Description suggests we have to find which ip address and port number that Malware.exe is connecting to.
So we can run the Malware and capture the packets using Wireshark.
During analysing we can see there is a http

![Screenshot from 2020-08-12 02-56-01](https://user-images.githubusercontent.com/47820151/90002372-6eec7380-dc47-11ea-9151-054ab0b77ce2.png)

So we can see that it is connected to 23.97.198.147 and port no.32847
from that link if we open, it returns the flag; **Poseidon{HUhu'R3G0OD4tD1gG1nG}**
