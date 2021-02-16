# techmino-dependencies
This repository holds binary dependencies for building Techmino ( 26f-studio/Techmino ) from source.

I am not familiar with the build process, but I will add more info if I learn more about it.

## Known sources of files
- `cold_clear.dll`: https://github.com/MinusKelvin/cold-clear
- `lua51.dll`: http://www.lua.org/
- `love.dll` and `love.exe`: https://love2d.org/

I am not aware of the sources of many of the files in there. Feel free to leave an issue and let me know.

## Build instructions
Here we are assuming you have the binaries of third-party dependencies. If you need build instructions for these, look for them separately - I don't know about these.

First of all, zip the Techmino repository and rename the zip as `game.love`.

### Windows x64
Append `game.love` to the end of `love.exe`. Place the resulting exe alongside with all the dlls.