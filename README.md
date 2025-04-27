# sault-jsfx-plugins
An assortment of synth and effect JSFX plugins meant for the Reaper DAW

It was long overdue to collect and archive some of these plugins, some of this code stretches back a decade!
Many of these plugins have dedicated pages in the Reaper Stash and forum.

Contains the st-oversampler.jsfx-inc library which has been used in a few different plugins throughout the community.

MGAZCM
  I use this one the most, it is a combination of the MGA limiter and a zero crossing maximizer with built in oversampling.

Super Slaw
  My take on the Roland Super Saw, implemented with variations of the sin() function. Crank up the mod index to get a little
  more of that classic sound. Multiple saturation options, detuning, width, etc. Great for pads!

Formant Function
  Sweepable formant filter, the cool part is that it morphs between two different formants. Can be set to automate through
  an envelope, through sidechain, or an "auto-wah" style. Adjust the sensitivity and the response curve to change how the
  filter reacts.

Gardner Small Room Reverb
Gardner Large Room Reverb
  Relatively straightforward adaptions of the Gardner reverb algorithm as proposed in "The Virtual Room" paper.

Elliptic Clipper
  Here I use elliptic filters to oversample a tanh() clipper.

