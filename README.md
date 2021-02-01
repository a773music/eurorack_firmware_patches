# Eurorack firmware patches
Distributed as is, apply at your own risk. 

## Rings
The patch will make (mutable) rings only jump in octaves on the frequency knob when patch chord in v/oct input

## Teletype
Based on [a textual explanation](https://llllllll.co/t/teletype-3-feature-requests-and-discussion/16219/379
) by user [jnoble](https://llllllll.co/u/jnoble) on the lines forum.  

* teletype_16_scripts_24_scenes.diff gives 8 additional scripts (11-18), the number scenes had to be cut to 24 due to memory limitations on the teletype
* teletype_12_scripts.diff gives 4 additional scripts (A-D), while keeping the 32 scenes (this patch is more or less unmaintained)