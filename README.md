# mpv-config-for-MPC-users

This settings will make mpv quite user friendly especially if you're coming from MPC.
Only some inputs are different.

## Inputs

- Page Up / Page Down : seek chapters
- -/+ (Substract/Add) : audio delay
- CTRL+-/+ : subtitles delay
- Left mouse click : pause
- Space bar : pause
- Left/right keys : seek video time
- Up/Down keys : Volume
- CTRL+Left/right : seek frame by frame
- Right mouse click : seek frame by frame
- s : screenshot (PNG + subtitles)
- HOME : restart playback
- Backspace : Play previous file
- Enter : Play next file

# Config

- Screenshots are named after filename+timecode in HH:MM:SS.ms and saved on Desktop
- MPV open in windowed mode fitting screen height
- Video accurate duration (HH:MM:SS.ms)

## Scripts

- Autoload.lua add automatic next file loading from the folder
- Ignore_images.lua prevent mpv to load common images files (avoid images opening between two video/audio files in a folder)



Note : subfont.ttf is Raleway-Medium font renamed.
