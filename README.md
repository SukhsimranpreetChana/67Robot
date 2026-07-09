# 6 7 Robot

The 6 7 Robot is a voice-activated robot that reacts when it hears “six” and “seven.”

It uses an ESP32-WROOM with an Edge Impulse audio model for word detection. When the correct sequence is recognized, the ESP32 controls a TT motor through an L298N motor driver.

## Parts

* ESP32-WROOM
* Microphone
* L298N motor driver
* TT motor
* VEX IQ battery and power switch
* 3D-printed base, body, and gearbox
* Bluetooth connection

## How It Works

1. The microphone listens for audio.
2. Edge Impulse detects the words “six” and “seven.”
3. The ESP32 checks that they were heard in the correct order.
4. The motor activates and the robot reacts.

Bluetooth can also be used for testing, debugging, or manual motor control.

## Setup

1. Assemble the 3D-printed parts.
2. Connect the motor to the L298N.
3. Connect the L298N and microphone to the ESP32.
4. Connect the VEX IQ battery through the power switch.
5. Train and export the Edge Impulse model.
6. Upload the firmware to the ESP32.
7. Test the “six, seven” command.
