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

## Design summary

The device can be built with a Raspberry Pi Pico microcontroller board
and a capacitive touch sensor. The details are in the `PCB` directory in
this repository.

In addition, to be able to use the touch sensor with the Pico, a
software library (firmware) is required. This firmware can be found in a
separate repository:
[antgon/pico-mpr121](https://github.com/antgon/pico-mpr121).
