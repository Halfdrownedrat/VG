# Raspberry Guide
## Pre Text
This isn´t a comprehensiv or general purpose guide for Raspberry Pi or micro electronics. The goal is to document the knowledge that is needet to run the pi for my projects, specificly for the VG project.

## Different Models
https://www.raspberrypi.com/news/raspberry-pi-product-series-explained/

## Other similar components
(Competitors that maybe do something better or are just cheaper)
http://www.orangepi.org/ 


## Operating Systems
### Difference 32bit 64bit Systems
Always use 64bit unless some component requires 32bit or your system is extremly old/weak.
### Difference Light Version and not
Light versions of OS are always smaller, faster and more compact. This is usally archived by removing any GUI (graphical user interface). For this project they are great, generally they require some more user knowledge about the command line. (Shell)
### Different Systems
#### Raspberry Pi OS
- General purpose OS for the raspberry
#### Ubuntu
- General purpose OS for any kind of device
#### Tails
- dement operating system (deletes all data and most programms on reboot)
- usefull if you´re paranoid or have goverment officials tracking you
- usually booted and used from an USB stick
- not usefull for this project
#### KDE Neon

#### ....
### Flashing OS
**On Windows**: 
- Rufus(fast, reliable, Open Source)
- Raspberry Pi Manager(very slow, easy to use)
**On Linux**
- Raspberry Pi Manager(very slow, easy to use)
- Terminal (a bit annoying but if done using Shellscripts or similar, really fast)

1. Choose the desired OS (usally Raspberry Pi OS Light 64 bit or an Ubuntu light version)
2. Get the .img file or choose it from the flashing tool
3. Erase/Formatt SD card
4. Burn OS on it (Read 5. before doing this)
5. Remember to enable SSH, set up user, add Internet connection
6. Eject SD card from reader, add to raspberry pi
--Finished--

## The components

## The pins

## Creating SSH connection
### Setup
A: Already set up before startign the Pi, great!
B: Not set up before, sad but managable
1. Connect any display and keyboard 
2. Log in
3. Enable in settings (differs between different OS)
4. Enable Wifi and add your local wifi if not already done
### Connecting
1. Go to device in same network 
2. Write: ssh localname@local or IP_Adress@local...
3. Log in
--Finished--
### Notes
- wireless keyboards can create some issuas, use cable bound to be sure
- After finishing the setup, you can remove everything (mouse, keyboard, display)
- being on a public or guest network might cause problems
- Firewalls (router, PC) might cause problems, add the device as an exception 
- Windows sucks and creates problems, please use linux
- You can connect to your Pi from outside the wifi using port forwarding and/or a VPN

## SSH from outside home
If you´re not home but need to check/change something, you can do that through a few ways.
**Quick Warning**
If you have a DS Lite connection, good look, it fucking sucks. (IPv4 adresses are limited so you´re Internet provider might sometimes just package your adress in a ipv6 adress, meaning you´re ipv4 is not reachable from the outside)
When port forwarding, the displayed  adress in eg. the Fritzbox Internet Site is usally not the real systems adress.
Most adresses are not static, meaning they change on reboot.

## Notes
**Put stuff regarding hardware in the corresponding tabs?**




## Sources
**Link Offical Documentian here**
### Videos
https://www.youtube.com/watch?v=IgnGFsLIL7U
https://www.youtube.com/watch?v=aDTxg5tfglA
### Offical guides
For Kids: https://www.raspberrypi.com/resources/learn/
All purpose tutorials: https://www.raspberrypi.com/tutorials/
### Courses
https://www.codecademy.com/learn/learn-raspberry-pi 
https://www.raspberrypi.org/courses/learn-python 
https://www.edx.org/learn/raspberry-pi
https://www.udemy.com/topic/raspberry-pi/ 
### Articels/ Blogs
https://learn.sparkfun.com/tutorials/python-programming-tutorial-getting-started-with-the-raspberry-pi/all 
https://www.jaycon.com/ultimate-guide-to-raspberry-pi/
https://www.tutorialspoint.com/raspberry_pi/index.htm

