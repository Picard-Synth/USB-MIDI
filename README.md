# USB-MIDI
DIY USB host - MIDI DIN converter

This is a USB host to legacy MIDI DIN converter based on FTDI’s VNC2.
VNC2 is a fully-fledged MCU with two USB controllers.
The complete USB protocol data processing is handled entirely by hardware so you only have to call APIs.
The VNC2 runs a proprietary RTOS.

With this board you can use USB-only MIDI controllers to drive traditional MIDI hardware.
USB power is also supplied. 
