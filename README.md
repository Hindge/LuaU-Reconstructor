<div align="center">

<img src="./Preview%20Logo.png" width="500">

A ServerScript reconstruction tool for LuaU.

</div>

## About

**LuaU Reconstructor** is a ServerScript reconstructor designed to allow users to recover and reconstruct accessible LuaU script fragments without relying on external methods.

The project works through remote logging and pulling accessible `LocalScript` instances, then uses the executor's decompilation function to reconstruct the retrieved script content into readable LuaU source.

## Accuracy

LuaU Reconstructor aims to provide one of the most accurate ServerScript reconstruction results possible.

While reconstructing a ServerScript can never guarantee a perfect **1:1 representation of the original source**, the reconstruction process is designed to get extremely close to the original logic and structure.

Reconstructed sources can be directly read and inspected, making it easier to understand the recovered logic, analyze script behavior, and work with the resulting LuaU source.

## Exporting

Once reconstruction is complete, LuaU Reconstructor can export the reconstructed contents as an openable **`.rbxm` model file**.

The exported `.rbxm` contains the reconstructed script contents in a Roblox-compatible hierarchy, allowing the result to be opened and inspected directly in Roblox Studio.

## How It Works

1. Logs relevant remote activity.
2. Identifies and retrieves accessible `LocalScript` instances.
3. Collects available script fragments.
4. Passes retrieved scripts through the executor's decompiler.
5. Reconstructs the resulting fragments into readable LuaU source.
6. Organizes the reconstructed contents into an `.rbxm` model.
7. Exports the model for opening and inspection in Roblox Studio.

## Features

- Highly accurate ServerScript reconstruction
- Reconstruction of accessible LuaU script fragments
- Remote logging
- LocalScript retrieval
- Executor-based decompilation
- Readable reconstructed source
- `.rbxm` export
- Openable Roblox Studio model containing reconstructed contents
- No external reconstruction methods required
- Designed to preserve as much of the original logic and structure as possible

## Limitations

No reconstruction system can guarantee a perfect 1:1 recreation of a ServerScript's original source.

Formatting, variable names, comments, structure, and other source-level information may not be preserved during decompilation or reconstruction. However, LuaU Reconstructor is designed to produce results that remain extremely close to the original script wherever the available runtime information allows.
