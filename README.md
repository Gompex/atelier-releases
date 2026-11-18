# Atelier: release builds


Atelier replaces FINAL FANTASY XIV's console-style windows with mouse-and-keyboard ones (Dalamud plugin):
a command palette (Win+Space, changeable), a one-screen Duty Finder, a Character window with a live 3D preview,
a Crafting & Gathering log with material trees, and a retainer roster. Every window can be switched off
to get the game's own back. One click does one thing; nothing runs on its own.

This repository only holds the release zips and `repo.json` for Dalamud. The source is not here.

## Install (once)

1. In game, type `/xlsettings` and open the **Experimental** tab.
2. Under **Custom Plugin Repositories**, paste this link, click **+**, tick it as enabled, then **Save and Close**:

   `https://raw.githubusercontent.com/Gompex/atelier-releases/main/repo.json`

3. Type `/xlplugins`, open **All Plugins**, search for **Atelier** and click **Install**.
4. Type `/atelier`, switch on the windows you want, and press **Win+Space** anywhere (change it in `/atelier`).

New versions arrive like any other plugin update.

Current version: **0.6.1.0** - 0.6.1: palette finds items, recipes and gatherables; customizable shortcut (Win+Space by default)