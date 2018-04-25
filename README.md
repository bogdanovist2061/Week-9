# Week-9 Project: Honeypot

## Honeypot deployed
I used Dionaea over HTTP as a honeypot for this experiment.

## Issues encountered
Most of the commands and installs worked smoothly once I figured out their context. What confused at me first was the location in which each command was supposed to be entered. For instance, the early commands in Milestone 1 worked when entered into the general Gcloud shell; however, I was thinking the Ubuntu VM was supposed to already be installed by that point, and that the given commands were supposed to be issued within that new VM.

Another issue I faced was exporting the .json file at the end. I could not get the Gcloud terminal to send the file to my local machine; the listed commands would work, but the file could not be found on my machine. I researched the file transfer commands and tried experimenting with them a bit to no avail. Most would just create new directories (with the name of the destination path I specified) on my Gcloud with the file in it, instead of sending it to the specified destination. Hence, my .json file is simply multiple copy-and-pastes of what I could get from opening the file in Nano.

## Summary of data collected
In the roughly two hour window I let this honeypot run, it collected close to 400 attacks. Many of these came from my own nmap performed on the honeypot, but many did not. An overwhelming majority of the attacks came from outside the US.

## Unresolved questions raised by data collected
I am curious to know what these types of attacks mean for cybersecurity in IoT, as well as what their sources or purposes may be. Are these run by port-scanning scripts linked to much more malicious intentions? Could foreign governments be behind these? How well can IoT devices protect themselves from port-scanning tools?
