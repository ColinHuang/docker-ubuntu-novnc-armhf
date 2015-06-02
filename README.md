## Ubuntu with noVNC for armhf architecture

noVNC is a HTML5 VNC client that runs well in any modern browser including mobile browsers. 

## Usage

The recommended way to run this container looks like this:

    $ docker run -d -p 6080:6080 colinhuang/ubuntu-novnc-armhf

This will start a container in a detached session in the background and will expose its web interface to port 6080 of the host. Now you can browse to:

[http://localhost:6080/](http://localhost:6080/) 

to access the Ubuntu desktop.

