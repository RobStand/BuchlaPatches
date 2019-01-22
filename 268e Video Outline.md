# Keen Association 268e video series
Welcome to the series of videos about Keen Association Graphic Waveform Generator Model 268e in the Buchla format.

## Overview
This module has four digital oscillators. Each oscillator has a virtual logger tape that is visible in this window. The core theme of the module is Recording CV on the virtual tape, which is played back as audio. As the CV is recorded on the virtual logger tape, You can see the resulting waveform in the window. You can control the speed of the virtual tape, input control voltages in differente ways, modulate the waveforms including AM and FM, get useful outputs like pulses, CV, and audio, and control pitch of each oscillators sepaately. And as an e-series module, you can store the settings in a preset.

In this video, I will go over the module's user interface. I'll explain how the virtual tape logger works in depth, cover the different ways of getting CV in and out, go over the modulation and control of the oscillators, and close with some tips and tricks.

## UI
The number "four" is a common theme of Buchla modules, and the 268e is no exception. With four oscillators, there are four pairs of individual outs, and an "all" output that unisons the four oscillators. I have each output going to ABCD sections of the 292e in combination mode.

### VTL
The next section is the virtual tape logger. The virtual tape logger is the unique and defining feature of this module. Imagine it as a tape flowing through the module at a set speed, and as you input control voltages, they are recorded, or written, onto the tape. As the tape moves through the module, the control voltages are rendered as a waveform, which is outputted as audio.

The algorithm determines how the 268e writes CV on the virtual tape. In other words, the algorithm defines how the logger will behave on input of CV. There are two algorithms, Continuous and m'detector, which can be selected with the Algorithm button. The continous algorithm makes the tape logger behave like a never-ending high speed reel that continuously captures CV and doesn't stop if no CV is input. This is like hitting record in your DAW: it will just record forever, even if there's no sound. The motion detector algorithm stays idle until some activity is detected and writes the CV on the tape as it occurs, kind of like a seismograph, which moves when there's an earthquake.

There's an orange pulse input that will change the algorithm when a pulse is received.

There are three ways to input control voltage into the 268e: the manual knob, the external CV input, and the control CV inputs. The manual knob is a potentiometer that moves a virtual stylus up and down the logger tape. Knob movements are available at the blue CV output.

The external CV input accepts CV of 0-10v and writes the CV to the logger tape. A pulse is generated each time the direction of the control voltage changes. The violet CV output is a differential function that send a voltage relative to the CV input: The faster the external input, the higher the voltage at the df output.

The control CV inputs accept external CV input, but the CV affects the individual oscillators instead of all at once. More on that in a bit.

The steady button behaves differently based on the selected algorithm. In continuous mode, it freezes the virtual tape until it is pressed again or an external pulse is recevied. In m'detector mode, it does an S+H on the active input and filles the tape with a constant value that results in a horizontal line. There is an orange pulse input that can be used to turn steady on and off.

The speed knob controls the rate of the logger tape, from slow to fast. The speed of the tape greatly affects the waveform that is rendered on the tape. I'll show you that a little later. There's a control voltage input and attenuverter to put speed under voltage control.

### Control input
The control and mouldation inputs section provide inputs for pitch, modulation input, and modulation depth per oscillator. Send pitch to each oscillator at the black CV inputs. The tinijax inputs provide for frequency and amplitude modulation. The gray CV inputs function similarly to the external input and will "draw" the waveform on the virtual logger for each specific oscillator independently.

### settings
In this section, you can set the base pitch for the oscillators, including fine tune. The mod bus handle knob activates the settings menu, where you can choose the modulation type and the inputs for the two algorithms. We'll cover that next. And there's a remote enable LED like you'll find on all other e-series modules.


## The virtual tape logger
As I mentioned earlier, The virtual tape logger is the unique and defining feature of this module.




### Continuous


### Manual input
