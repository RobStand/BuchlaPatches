# Part 2

The continous algorithm makes the tape logger behave like a never-ending high speed reel that continuously captures CV and doesn't stop even if no CV is input. This is like hitting record in your DAW: it will just record forever, even if there's no sound. The motion detector algorithm causes the tape to stay idle until some activity is detected and then writes the CV on the tape as it occurs, kind of like a seismograph, which writes to a tape when it detects movement. There's an orange pulse input that will change the algorithm when a pulse is received.

With the continuous algorithm selected, the virtual tape flows through the module and turning the knob draws on the tape. When you stop turning the knob, the tape keeps flowing. In motion detector mode, the tape moves when you turn the knob. When you stop turning the knob, the tape stops. Knob movements are available at the blue CV output, so you can use the knob as a CV source for other modules.

### settings
In this section, you can set the base pitch for the oscillators, including fine tune. The mod bus handle knob activates the configuration menu, where you can choose the modulation type and the inputs for the two algorithms. We'll cover that next. And there's a remote enable LED like you'll find on all other e-series modules.

## External algorithm
Earlier you saw the two algorithms work when the 268e is in "manual" mode. Now let's take a look at how the algorithms work with External input. First you have to set the algorithms to the input source. TO do that, click the Mod Bus Handle knob and set each algorithm to external. There's a third option, Individual, that we'll go over in just a bit. Hit the Steady button to exit the settings screen and now the 268e is ready for external input.

Let's start with a straightforward CV from the 281e. The algorithm is set to Continuous, so any CV that goes into the external input will be drawn. I've got the speed set to around 5. Let's send the D section of the 281e to the external input, set the 281e to self cycle, and see what happens. The "stylus" drawing on the virtual tape is being controlled by the CV coming into the External input from the 281e. As I change the attack and decay on the 281e, the waveform changes. When I take the 281e out of self-cycle mode, the virtual tape keeps going and our waveform disappears.

Now let's switch the algorithm to motion detector. I'll put the 281e back into self cycle mode. When the incoming CV goes above 0v, the virtual tape will advance and the stylus will draw the waveform.
