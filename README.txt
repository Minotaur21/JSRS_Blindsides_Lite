This is a patch to improve performance when using JSRS and Blindside's Weapon Reanimation.

How to install:

1) You will need to install ALL THREE required mods in the order shown below. Read the mod descriptions for instructions on how to install them.
 - JSRS Sound: https://www.moddb.com/mods/stalker-anomaly/addons/solarint-gunshot-overhaul
 - Blindside's Weapon Reanimation: https://www.moddb.com/mods/stalker-anomaly/addons/blindsides-weapon-reanimation-and-rebalance-loner
 - Blindside's JSRS Patch: https://www.moddb.com/mods/stalker-anomaly/addons/blindsides-weapon-reanimation-and-rebalance-jsrs-patch

2) Install this `JSRS+Blindsides Lite` mod.
 - I recommend using a mod manager such as Mod Organizer.
 - If you want to install manually, just drag the gamedata folder into your Anomaly folder. Let it overwrite if it asks.
 - My mod will be incompatible with anything that overwrites the weapon_sounds.ltx file, so be careful if you install other mods after this.
 
Mod Description:

My JSRS+Blindsides Lite Patch raises performance by reducing CPU load for people who play with JSRS and Blindsides.

In the original JSRS, each gunshot triggers multiple sound layers per shot to create the wonderful and complex sounds that you hear. This also applies to NPC gunshots.
Large-scale firefights in populated maps with many NPCs all firing at once means that the CPU load increases drastically as it tries to process all of the sound layers.

Most people's PCs can handle these scenarios without extreme performance loss, but for some people who don't have great CPUs or who want to maximize performance, this patch will come in handy.
The patch is a simple edit to reduce the overall number of sound layers per gunshot. The number of layers have been reduced by roughly half.
This will allow you to play in densely populated maps with lots of AI combat without losing too much performance or needing to remove JSRS.
Please note that reduced sound layers means the sound quality will be slightly worse than JSRS's sound quality. That is a tradeoff you must be willing to make to improve performance.

This sort of patch was originally created by `nb79` here for JSRS only: https://www.moddb.com/mods/stalker-anomaly/addons/jsrs-cheap-version
I studied nb79's configs and used what I learned to reorganize Blindside's own JSRS Patch. All sound files in my patch originally come from JSRS, and credits for these sounds go to Solarint.
Thanks to Solarint, Blindside, and nb79 for their work.