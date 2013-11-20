tf2cfg
======

My Team Fortress 2 configuration scripts

Usage
-----

All common in-game settings (like sensitivity, field of view, and most keybinds)
are in mydefaults.cfg, which is executed by each class-specific config. The
autoexec.cfg file contains the technical settings and the configs that I only
want to execute once, like billnyetho.cfg, which would otherwise have its counter
reset every time I respawned.

Installation
------------

Clone this repo to ```Steam/SteamApps/common/Team Fortress 2/tf/custom```. The folder
structure must follow ```Team Fortress 2/tf/custom/tf2cfg/cfg```. See
```Team Fortress 2/tf/custom/readme.txt``` for more details on mod installation.

Launch Options
--------------

I also start TF2 with the following launch options:

```-threads 4 -full -w 1920 -h 1080 -console -novid -useforcedmparms -noforcemaccel -noforcemspd```

Sources
-------
- [Chris Down's TF2 Configs][chris]
- [Ideal Network Settings for Spy][stabbynet] by stabby stabby
- [A Somewhat Formalized Topic on Matters of Backstab Detection][formal] by ParanoidDrone
- [Thrax's Quality Config][thrax]
- Various credits given in individual files

[chris]: https://github.com/tf2configs/tf2configs
[stabbynet]: http://forums.steampowered.com/forums/showthread.php?t=2765833
[formal]: http://forums.steampowered.com/forums/showthread.php?t=1788631
[thrax]: http://icrontic.com/discussion/93420/max-quality-config-for-tf2
