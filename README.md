# Mixxx mapping for Launchpad mini

In this repository you will find Bass The Wise's Mixxx mapping for Novation's Launchpad Mini, which has been modified by Whanake for the Launchpad Mini Mk3.

This mapping is largely based on jdsilvaa's work (https://github.com/jdsilvaa/mixxx-launchpad-mini), itself based on marczis and zestoi previous mappings for the controller. There is also a more advanced mapping from dszakallas (https://github.com/dszakallas/mixxx-launchpad); give it a try if you are looking for a very complete controller of 4 decks and 4 samplers!

This mapping for Mixxx will turn your launchpad into a simple 2 deck mixer, with support for filters, 4 FX, 16 samplers, library browsing and AutoDJ. It is based on Mixxx's version 2.2.4, changing some deprecated controls used in the script that I reworked.

To try it, you will need to copy the xml and js files into Mixxx's user controller folder. When starting Mixxx, go to Preferences / Controller, and select the Launchpad controller on the left side. Then choose Novation Launchpad Mini by bassthewise from the Load Mapping list, and make sure to tick the Enabled box.

This is a summary of the functionalities:

· 1st page is a 2 deck mixer, with track progress, Play, Cue, PFL, Sync, FF/RW, Sync+/-, 4 Hot Cues, 4 Loops, reloop, pitch, crossfader and volume controls.

· 2nd page is for the SuperFilter and Filters on the 2 decks.

· 3rd page is for 4 FX: assigning to decks, first meta knob and mix controls for each FX. I didn't manage to enable the filters with the script, so you'll need to activate the first effect on each FX deck for this to work.

· 4th page is for Master Volume and Headphone volume, plus gain and volume control on the 2 decks. It has peak controls for each deck

· 5th page is for Samplers 1-8 with gain; samples will always start from the beginning.

· 6th page is for Samplers 1-8 again, but instead of gain it has PFL, FF/RW, Sync+/-, and hotcues 1-4.

· 7th page is for Samplers 9-16 with gain; activating repeat, quantize, keylock and beatsync on the samples. It is meant to be used with drum samples.

· 8th page is for Library Navigation, loading tracks to deck 1, deck 2, samplers 1-8, and the AutoDJ playlist. There are controls for the font size, waveform zoom, toggle Maximize library, and enabling AutoDJ. It also shows the progress of each track.

The more or less detailed function for each button is as per this image:
![Novation Launchpad mini_MIXXX mapping](https://user-images.githubusercontent.com/81437860/113695764-880fcc00-96d1-11eb-930f-80eddde7412a.png)

Special thanks to Bass The Wise for most of this README.md, as well as everyone that worked to make this mapping possible. All I did was reformat a few things to work with the latest version of the Launchpad Mini series.

Enjoy!

Bass The Wise (Edited by Whanake)
