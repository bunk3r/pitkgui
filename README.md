# pitkgui
A tkinter GUI for raspberry pi + adafruit 2.8 display (pitft)

![pitkgui screenshot](https://raw.githubusercontent.com/bunk3r/pitkgui/master/screenshot.png)

Due to Pygame+touchscreen problems in Jessie, it's time to use Tkinter.

console config:

- Launch with:  `xinit /usr/bin/python /path/to/pitkgui/pitkgui.py`
 
- Autostart from console: 
 * add `xinit /usr/bin/python /home/pi/Develop/pitkgui/pitkgui.py` to /home/pi/.profile
 * autologin to console with raspi-config
