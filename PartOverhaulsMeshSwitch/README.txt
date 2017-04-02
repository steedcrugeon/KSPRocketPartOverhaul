PartOverhaulsMeshSwitch Readme

Art assets by Porkjet / SQUAD
Licence: CC-BY-NC 3.0


Plugin code by Michael Billard (Angel-125)
License: GPLv3

Description
Porkjet's design sheet proposed three different configurations for the rocket engine overhaul: Standard, Boat-Tail, and Compact. The design sheet suggested using mesh switching to accomplish this. Mesh switching is the combining of several 3D models into one .mu file, and showing or hiding the 3D model depending upon the configuation. After examining the art assets generously provided by SQUAD, I realized that I could bring Porkjet's vision into reality by writing a mesh switch plugin and rearranging the art assets a bit. With this modified PartOverhauls, you no longer have two separate engines for the LV-series (T15, T30, etc.). Instead, you have one combined engine that lets you switch between the Standard and Boat-Tail configurations. The rest of the engine parameters remain the same.

Folder Descriptions
GameData: Contains the modified PartOverhauls by SQUAD along with the plugin by me. Simply replace your existing PartOverhauls in your GameData folder.

Switchers: Contains the source code for the mesh switch. The current version doesn't support changing the attachment rules for the part, but hopefully the next version will. I also plan to add a check to see if certain part upgrades have been purchased; you could have alternate engine nozzle configurations that way, for instance.

ArtSource: Contains the .unity files for each modified rocket engine. You MUST download SQUAD's PartOverhauls art assets to make use of this; space limitations required me to leave the full source out.

Thanks again to SQUAD for making the art assets available. :)