# Very Simple  USB Macropad

Very simple and easy to understand code to make your own custom macropad. Each key switch requires its own pin on the pro micro. This is not the optimal configuration but make it very easy to use. 

Please ignore the photos in the pics folder I have changed the wiring. I have each key switch connected on one pin to the common ground and the other pin is directly connected to it's own pin. This limits the number of switches you can add to the circuit to the number of pins on your board instead of using a switch matrix.

Currently the code does not support the encoders.
![alt text](https://i.imgur.com/JUtJT0c.jpg "4x4")


# Setup

## Wiring 
To wire up a key connect one of the pins of the momentary switch to ground and the other pin to a digital pin 2-21. The switch will activate the key when the pin is shorted to ground then it will delay so that the key is not input more times than desired.

## Program Pro Micro
To program click the verify and upload then quickly enter bootloader mode. If you don't do it fast enough it will not connect.

## Enter Bootloader Mode 
To enter bootloader mode on the pro micro short the rst pin to the ground pin twice quickly. This will keep it in bootloader mode for 8s.

# Microsoft Teams Shortcut keys
Accept video call    Ctrl+Shift+A

Accept audio call    Ctrl+Shift+S

Decline     call Ctrl+Shift+D

Start audio call     Ctrl+Shift+C

Start video call     Ctrl+Shift+U

Toggle mute  Ctrl+Shift+M

Toggle video    Ctrl+Shift+O

Go to sharing toolbar   Ctrl+Shift+Space

https://support.office.com/en-us/article/keyboard-shortcuts-for-microsoft-teams-2e8e2a70-e8d8-4a19-949b-4c36dd5292d2

