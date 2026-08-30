<div align="center">

<img src="./Preview%20Logo.png" width="500">

A ServerScript reconstruction tool for LuaU.

</div>

## About

**LuaU Reconstructor** is a ServerScript reconstructor designed to allow users to recover and reconstruct accessible LuaU script fragments without relying on external methods.

The project works through remote logging and pulling accessible `LocalScript` instances, then utilizes the executor's decompilation function to reconstruct the retrieved script content into readable LuaU source.

## How It Works

1. Logs relevant remote activity.
2. Identifies and retrieves accessible `LocalScript` instances.
3. Collects available script fragments.
4. Passes retrieved scripts through the executor's decompiler.
5. Reconstructs the resulting fragments into LuaU source.

## Features

- ServerScript reconstruction
- Remote logging
- LocalScript retrieval
- LuaU fragment reconstruction
- Executor-based decompilation
- No external reconstruction methods required
