# Choosing a toolhead

Rudy uses a front facing mgn9c carriage, so any toolhead that supports that
should work. You ideally want something that's as small on x and y as possible
to not limit travel. If you are using limit switches, you also want to make sure that your toolhead can hit those. 

## Warhead

The Warhead is a custom design specifically made for Rudy. It uses a V6 hotend
with a 3010 fan and a 4010 blower for part cooling. Since it's not strictly a 
part of the Rudy project, it has its own repository and BOM, but if you purchace
the Rudy BOM, you should have enough leftovers to build it too.

Pros:

    - tiny, barely bigger than a V6
    - prints quickly
    - uses standard parts

Cons:

    - in active development
    - the part cooling is okay at best, this is being worked on

[Warhead](https://github.com/RazorSh4rk/warhead)

## Rookery

The Rookery is a very well designed toolhead from Gulsifer on the Rook discord.
It uses the same mounting style as Rudy so it should work too.

Pros:
    
    - much more mature design
    - supports different hotends

Cons:

    - default hardware is very weird, it uses both MK8 and Volcano parts
    - slightly more expensive to source
    - I personally am not convinced of its hotend cooling capability
    - big, it will limit x and z travel

[Rookery](https://www.printables.com/model/381953-rookery-bowden-tool-head)

## DDRudy

DDRudy is a direct drive toolhead custom-designed for the Rudy printer by @skillenmcnot. It is based off the Orbiter v2 extruder and the Trianglelabs CHC Mini hotend.
Other hotend and extruder combinations are possible, although a different extruder may require moving the mounting hole positions in the model.

Pros:
    
    - custom designed for Rudy
    - supports different hotends and common replacement parts
    - excellent cooling performance
    - actively being improved
    - editable model files available

Cons:

    - requires a moderately well-calibrated machine to print properly
    - wider than Warhead, it will limit x travel to 90mm

[DDRudy](https://github.com/skillenmcnot/DDRudy)

# Salad fork

The Salad fork uses the same rail for x, and the modified the mini afterburner
and the mini stealthburner from the voron 0 to fit that. While this is currently
not officially supported on Rudy, i don't see any reason why it couldn't be 
used.

[Salad fork](https://github.com/PrintersForAnts/Salad_Fork/tree/master/STL/Toolhead)