Instructions:

Download the .zip file for the version you want to use (contains the folder
'data' and file 'pack.mcmeta') and place it in the datapacks folder of your world:

- v2.0.0 requires you click on a banner to set the target location there
(similar to creating Map Markers). Also contains a custom recipe [4 iron + 1 quartz].

- v1.0.0 doesn't fuss with banners, but still contains the recipe.

- v0.1 is stripped down to just the basics. To get the satnav you'll have to
enter the command: /function satnav:give

With v0.1 & v1, the first right-click sets the target at your current location.
Moving and clicking again will reset it there; clicking twice in the same spot will
clear the satnav and stop it tracking.

v2 uses raycasting to identify the block the player is *looking at*,
rather than where they're currently standing.


Commands:

To give yourself a satnav without crafting (necessary in v0.1):

/function satnav:give


To remove all objectives from scoreboard:

/function satnav:dispose

(use /reload to reload all data packs)


To display in-game help:

/function satnav:_help


(If you're in a single-player world and can't run commands,
just open your world to LAN with 'Allow Cheats: ON' from the pause menu.)


=================== CREDITS =====================

I referred to a couple data packs by MSpaceDev
at https://vanillatweaks.net/picker/datapacks/
as a base for some of the trickier functionality (read: raycasting, custom item).

Satnav should *hopefully* play nice with any of those packs,
if you happen to be using them.

Any questions/issues/suggestions? I'd be happy to hear from you.


almostambidextrous
June 2019

https://www.reddit.com/r/Minecraft/comments/c49t5d/satnavgps_data_pack_java_113_displays_relative/