# cs2-immiecfg
# immiecfg
A simple and customisable config for cs2. 

### Features
* user settings - fps, hud and radar, viewmodel, audio, voip - commands commented and explained.
* shorthand cvars - map shorthands, 'prac' for practice, jumpfix alias.
* crosshairs - crosshair presets, crosshair color and style presets.
* practice config - offline practice server setup in just one command: 'prac'
* binds - my binds, every command commented, for easy reconfiguration.

> [!WARNING]
> When executing immiecfg/binds it will: unbind all your binds, then overwrite your local config (steam/userdata) using host_writeconfig, making your old binds toast.

I'd reccomend making a copy, change to your current binds and then execute whenever you need updating them.
Having your own bind cfg is nice if you change/switch pcs or accounts, or in case you lose all your steam data/windows reinstall.

### Installation
1. Get the files
  - Clone the repository or
  - Download a release from the releases page
2. Go to: Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
3. Place autoexec and immiecfg folder inside the cfg directory.
4. Open up CS2 and the autoexec will have ran.

You can also type 'exec autoexec' in the console, and the cat banner should show.

Last updated: 15/06/24
