# Frogman Magmaborn Assets
This repository contains most of the graphic & sound assets from [Frogman Magmaborn](../../../FrogmanMagmaborn). It's a bit messy since it was originally intended for personal use only, but it should hopefully be a bit easier to navigate than the final Assets folder from Frogman Magmaborn.

Also, it contains easier to edit source files for most assets (layered image files for graphics and midis for sound), and some old & scrapped assets for the curious.

## Graphics
This folder contains most of the 2D images & animations - a few of them (mostly parts of the UI) are only available in the Frogman Magmaborn repository, however.

Almost all of them were made in Realworld Paint - to open the layered image versions (`*.rli` files), you would probably need to download it. Some of the older animations were saved as an animated PNG, which not all editors support I think, so keep that in mind.

## Models
This folder contains the 3D models from the Endgame.

All of them were made in Blender, then edited & animated in Unity - so the source files aren't super useful on their own, but they're there I guess. The folder contains the original `*.blend` files and exported `*.fbx` files.

## Music
This folder contains all music files.

There are 4 files for each track: the original `*.json` file for BeepBox, the `*.midi` file exported from BeepBox for gxscc, the final `*.ogg` file exported from gxscc, and another ogg file (`* (original).ogg`) with the output from BeepBox.

The `Convert.bat` file converts all `*.wav` files (from BeepBox & gxscc) to `*.ogg` files.

## SFX
This folder contains all sound effects from the game.

Most of the files here are just the final `*.ogg` file, made with BeepBox and gxscc. There are also a few original `*.midi` files, however.
