# Vitruvian for Charmorph

Vitruvian is a Realistic Character for Charmorph.

It is based on a modified version of [Antonia Polygon] (https://sites.google.com/site/antoniapolygon/) and has been given permission by it's original author to be relicensed.


## Usage:

 Enable Screen-Space Reflections and Refractions to get normal looking eyes in EEVEE
 Change `No` for Expressions to `Character` or `Character+Assets` to get "FACS" shapekeys.

## Features:

* High Degree of Realism for an Open-Source Model
* 100+ Morphs
* 100+ FACS shapekeys including ARKit, Phonemes/Visemes, Expressions and mouth movements including tongue.
* Gender Neutral morphing allows for many more unique combinations compared to competitors.
* 4K UDIM Textures, source available for 8K texturing and customization
* Volume Preserving Rig
* Support for Many UVs, Including 3D Scan Store, Texturing.XYZ, Digital Emily and more.

## Downsides

* lacks dedicated picker menus for FACS that other software has. Blender issue
* Limited skin tones, Only supports Black & White textures, with the rest being blended linearly or supports custom [Physically Based Skin tones] (https://half4.xyz/index.php/2020/08/18/introduction-physically-modeling-skin-tones/) 
* FACS & Morphs can be quite limited at the moment. Either contribute or talk to us on Discord so we can get an Idea on what is missing.
* Unreal Engine Mannequin will likely never be fixed due to how Unreal's Mannequin relies on corrective blendshapes.
* Metahuman UVs will likely remain, Mostly broken due to the fact that Metahuman puts very little Emphasis on any uvs outside of the Face area. Which makes adapting them a Nightmare.

## Installation manual

Go to your charmorph folder, at `%APPDATA%/Blender Foundation/[INSERT YOUR BLENDER VERSION]/scripts/addons/[INSERT YOUR CHARMORPH DIRECTORY]/data/characters/` 
Extract the files to a folder called `Vitruvian` in the `characters` folder. The end result should look something like this:
`%APPDATA%\Blender Foundation\Blender\4.1\scripts\addons\CharMorph-master\data\characters\Vitruvian`
Although this should be already included in future releases.
## Links

* Discord server: https://discord.gg/bMsvxN3jPY
