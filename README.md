# inControl
In C, in PD, with midi controls

Open the file incOpen.pd to run. Click the green button to start, or send control voltage through midi cc number 41.
To stop or reset at any time, click the red button, or send voltage through midi cc 48.

Click the blueish buttons on the corner of each of the 8 stations to advance each instrument forward by 1 pattern. Alternatively, send a cc through midi cc #33-40. Volume for each instrument is midi CC #1-8; volume for the metrobeeps (the piano C's) is Midi CC 9, and the master volume is Midi CC 10.
If you'd like to edit any of the instruments, feel free to open up incOrchestra and scroll down. inc_clarinet~ is what it sounds like, and inc_fmsynth~ is a single-operator fm synth. The arguments are ratio, low index, high index, adsr for the volume, adsr for the synth amount (from low to High to low index multiplied by the ratio. Release is in ms, to 0 modulation.) For example, 16 1 3 10 20 .5 100 10 20 .5 100 would go from modulation amount of 16 to 48, then back down to 32 over the first 30 milliseconds of the sound.

For questions, email me at noisecomps@gmail.com

D Sprinkle
