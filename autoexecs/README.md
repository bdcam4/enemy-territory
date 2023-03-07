# Spawn selector script

Place all autoexecs into etmain and bind these to your preferred keys. 

There are some exceptions but usually they will follow this pattern:

bind UPARROW        "vstr sp_0"     // forward spawnpoint <br>
bind DOWNARROW      "vstr sp_1"     // spawn back <br>
bind LEFTARROW      "vstr sp_2"     // CP <br>
bind RIGHTARROW     "vstr sp_3"     // alternative spawnpoint (when applicable) <br>

bind BACKSPACE "setspawnpt 0; say_teamnl ^0<-- ^3* ^70 ^[auto"

**Note:** some spawnpts will be labelled as fast/slow. Fast spawns in front and slow spawns you behind to avoid blocking.