Ubuntu-RDP
==========

LXDE stands for .Lightweight X11 Desktop Environment.. LXDE is an energy saving and extremely fast and performing desktop solution. It works well with the low end computers of the performance spectrum such as new generation netbooks and other small mobile computers. LXDE is designed for cloud networks such as local freifunk clouds or the global Internet cloud. It can be built on top of various Linux distributions such as Ubuntu, Debian or Fedora.

GUI Graphical Desktop LXDE http://www.lxde.org/ on Ubuntu VPS server with low RAM configuration. This works even in VPS plan with 128MB RAM, run Firefox, Openoffice and other programs. This tutorial differs from Gnome GUI Desktop tutorial, because here we will install LXDE desktop, which is more suitable for a low RAM VPS plans.

For LXDE desktop installation we choose any minimal Ubuntu version (latest recommended) But I test it on ubuntu 10.10 also. Reinstall your VPS with minimal Ubuntu OS and log in to your VPS server ssh command line as .root..

Requirements :
- Any minimal Ubuntu version vps
- Putty to connect with your vps server
- Real Vnc Viewer Or Tight Vnc


add these two at the end of nano ~/.vnc/xstartup
lxterminal &
/usr/bin/lxsession -s LXDE &

use this to start VNC server
vncserver :1 -geometry 1024x768 -depth 16 -pixelformat rgb565
