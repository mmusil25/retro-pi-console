# retro-pi-console
Design documentation and project artifacts for a raspberry pi console emulator for retro video games. 

##Results

Here's a link to a [YouTube Video of Cave Story](https://youtu.be/Z5ow7Hn4VNo) starting up. 



## System Model (SysML Diagram)

![The System Model of the Console](system-model.png)

## Abstract

It has always been a goal of mine to build the classic Raspberry Pi console emulator. It's a fun exercise in using the popular linux hardware platform. My roommate really wants a retro console so the situation alligned just right for me to be able to build it. 

In this README I will detail how I planned and executed the project. 

## Parts
![Controllers, HDMI, and USB splitt](ctrl-hdmi-usb4.jpg)


![case-charger-keyboard](case-charger-keyboard.jpg)


![case-charger-keyboard](case-charger-keyboard.jpg)


### Raspberry Pi detailed model

# Timeline

### Research Phase

I was able to find plenty of web pages detailing how to make such a RaspPi console. 

My first Google search led me to this [PCWorld Article](https://www.pcworld.com/article/406449/how-to-build-a-raspberry-pi-retrogaming-emulation-console.html) which detailed the hardware I needed. In general, the parts list is pretty obvious. I have included a .CSV file on my parts list in this directory. 

```
retro-pi-console/Retro-Pi-Parts.csv
```

After doing some further reading I found that there are several competing platforms. The one that the PCWorld Article uses is called RetroPi. But there is also another project called RecalBox. However when the parts arrived and I tried to run standard RetroPi it couldn't handle it so I found a Lakka which is a [lightweight version of RetroPi]([url](https://www.lakka.tv/get/windows/rpi/)https://www.lakka.tv/get/windows/rpi/). And this one ran well. 

### Software Install

All you need 
