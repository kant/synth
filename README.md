# SYNTH
A Teensy 4 eurorack synth 

This is a work in progress.

The current schematics need to be reworked to solve some issues.

## Features

* FM synthesis with 1 carier and 1 modulator
* 16 voices polyphony
* Sine and triangle waveforms
* Arpeggiator and Drone modes
* Glide
* MIDI over USB
* MIDI over mini jack
* Audio jack output

## Getting Started

### Prerequisites

What things you need to make it work:

```
1 Teensy 4.0
1 Teensy audio board
1 MOTHERBOARD6A pcb
1 MOTHERBOARD6B pcb
1 SYNTH front panel pcb
6 vertical potentiometers 10K
3 14 pins male header
5 14 pins female header
4 CD4051 multiplexers
4 DIP16 IC sockets (optionak)
2 3.5mm jack connectors
1 resistor ~ 80ohm
1 LED
1 4 positions dipswitch (optional)
```

# How to use

Here is a description of the 6 inputs and what they do:

```
1. Mode
    1. Synth
    2. Arp
    3. Drone
2. Param
    1. Synth: Glide
    2. Arp: Time             
     . Arp with Midi clock   (TODO)
    3. Drone: Free frequency
3. Shape
    . Sine / triangle
4. FM
    . Modulator frequency and amplitude
    . 3 divisions:
        1. 0 to 10Hz, low amplitude
        2. 0 to 40Hz, low amplitude
        3. 0 to 1000Hz, higher amplitude
5. Attack                    (0 to 2000ms)
6. Release                   (0 to 2000ms)

```

## About me
You can find me on Bandcamp and Instagram:

https://ghostintranslation.bandcamp.com/

https://www.instagram.com/ghostintranslation/

https://www.youtube.com/channel/UCcyUTGTM-hGLIz4194Inxyw

https://www.ghostintranslation.com/


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details