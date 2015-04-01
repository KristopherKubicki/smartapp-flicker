# Gaslight Emulator
Emulate a low oxygen gas light flicker with low quality LEDs and Dimmers

I've always liked the way gas lamps looked for external lights, but they are very expensive and dangerous. 

<img src='http://carolinalanterns.com/images/t560x560/content_14.jpg'>

I noticed when playing around with low quality LED bulbs, I could get the bulb to "flicker" similar to a low oxygen gas lantern if I switched between certain thresholds.  First generation dimmable bulbs do not like the 50-60% range, for example. 

I discovered that by telling a dimmer to transit 59% once a second or so, I could get the bulb to flicker in a somewhat random fashion.  It is not as nice as a gaslamp, which has a very neat physical flickering property called 1/f or <a href='http://en.wikipedia.org/wiki/Pink_noise'>Pink Noise</a>.

Please feel free to mess around with this SmartApp as you will, but also keep in mind that the reason these low quality lights flicker is probably because some kind of physical damage is occuring to the bulb.  Any damage caused by this code is solely your responsibility. 

License
-------
Copyright (c) 2015, Kristopher Kubicki
All rights reserved.
