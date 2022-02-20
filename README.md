# mpv-config-for-MPC-users

This settings will make mpv quite user friendly especially if you're coming from MPC. A lot of key bindings are taken from MPC, but some others are custom because I find it more user-friendly.
Only some inputs are different.

On Windows, copy all files to "C:\Users\XXXXX\AppData\Roaming\mpv" (create the mpv folder if there is no one).

## Inputs

- f / F11 : Fullscreen on/off
- ESCAPE : escape fullscreen mode
- Page Up / Page Down : seek chapters
- Mouse wheel : volume
- -/+ (Substract/Add) : audio delay
- CTRL+-/+ : subtitles delay
- Left mouse click / Space bar / p: pause
- Left/right keys : seek video time
- Up/Down keys : Volume
- CTRL+Left/right : seek frame by frame
- Right mouse click : seek frame by frame
- s / F5 : screenshot (PNG + subtitles)
- CTRL+s : screenshot (PNG + no subtitles)
- HOME : restart playback
- Backspace : Play previous file
- Enter : Play next file
- TAB : change subtitles tracks
- a : change audio tracks
- F6/F8 : Decrease/increase playback speed
- F7 : restore playback speed
- i : display/hide informations

## Config

- Screenshots are named after filename+timecode in HH:MM:SS.ms and saved on Desktop
- MPV open in windowed mode fitting 85% of screen height
- Video accurate duration (HH:MM:SS.ms)

## Scripts

- Autoload.lua add automatic next file loading from the folder
- Ignore_images.lua prevent mpv to load common images files (avoid images opening between two video/audio files in a folder)



Note : subfont.ttf is Raleway-Medium font renamed.
