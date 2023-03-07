# Spawn selector script

Place all autoexecs into etmain and bind these to your preferred keys. 

There are some exceptions but usually they will follow this pattern:

<code>bind UPARROW        "vstr sp_0"     // forward spawnpoint</code><br>
<code>bind DOWNARROW      "vstr sp_1"     // spawn back</code><br>
<code>bind LEFTARROW      "vstr sp_2"     // CP</code><br>
<code>bind RIGHTARROW     "vstr sp_3"     // alternative spawnpoint (when applicable)</code><br>

<code>bind BACKSPACE "setspawnpt 0; say_teamnl ^0<-- ^3* ^70 ^[auto"</code><br>

**Note:** some spawnpts will be labelled as fast/slow. Fast spawns in front and slow spawns you behind to avoid blocking.