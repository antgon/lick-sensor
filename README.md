# Lick sensor

An open source device for measuring licking behaviour in rodents in real
time.

This is an easy-to-build lick sensor that does not require grounding,
can be used in any experimental setting with standard water bottles or
drinking spouts, and detects licks in real time with millisecond
precision. This system, based on capacitive touch sensors, is
inexpensive, can be connected to a variety of data acquisition systems,
and can be used for real-time control of additional hardware such as
LEDs for optogenetics.

2021-2023 Antonio González

## Files

The device consists of the hardware, which is based on a Raspberry Pico
microcontroller and a capacitive touch sensor, and the sofwtare
(firmware) that allows the touch sensor to be used with the Pico.

Details of the harware are included in the `PCB` directory. The firmware
is in its own repository: [pico-mpr121](https://github.com/antgon/pico-mpr121)
