

 <!-- What I need to add -- StackEdit to see how the README looks like -->
<!--  -->
 <!-- Screenshot/gif for "Easy method for finding this data" -->
 <!-- Contents table for README -->


# CS:GO Config - alby
<!-- Add issues etc. -->

## Important Info
- This will overwrite your default ```config.cfg```
To stop this, delete the line, "```host_writeconfig```" at the bottom of the file.

## Installation & Usage
There are a few methods to getting this config - the simplest being to copy the RAW
[Gist: autoexec.cfg] or [RAW: autoexec.cfg]
and save below.
C:\Program Files\Steam\userdata[your Steam ID]\730\local\cfg\
>**Note:** this is wherever Steam was installed (may not necessarily be C:\Program Files)

If you'd like to create a GitHub repo of this yourself, ensure you have an account - then simply hit the **Clone/Download** button and create your own.

I've also included a ```bots.cfg``` config which I will be updating in the near future.
This config will be designed for practice mode with toggles for grendade tracers etc.

>**Note:** This installation assumes that the *.cfg file is named ```autoexec.cfg```

### Adding the config to launch
- Library | Right-click CS:GO
- Properties | Set Launch Options
- ```+exec autoexec.cfg```


### Launch Options
My config quick copy
```-high -novid -tickrate 128 -console -developer 1 +exec autoexec.cfg```

Optional config
|Parameter|Purpose|
|-|-|
|```-high```|Sets game to high priority in Task Manager|
|```-novid```|Ignore videos on open|
|```-tickrate 128```|Sets default update rate to 128 tick, will switch to 64 for comp/casual|
|```-noborder```|Removes windowed borderless|
|```-w 1920 -h 1080```|Resolution|
|```-console```|Opens console immediately after launching the game|
|```-developer 1```|Console set to developer (unnecessarily necessary)|
|```-insecure```|For testing the goods (no VAC)|
>Note: Remember to add ```+exec autoexec.cfg```

## My Config
>**Note:**  I wont go through every single keybind / command - if you'd like to know, simply open the ```autoexec.cfg``` file and go through it.

|Console command / key| Purpose|
|:-|:-|
|```developer 1```|Similar to ```-developer```, it will enable the extended console|
|```i = toggle cl_crosshairsize 4 1000```|This changes between normal crosshair (4) an grenade lineup crosshair (1000) - change (4) to suit your crosshair.|
|```j = toggle gameinstructor_enable 1 0```|This turns on instructor which helps for finding bombs in smokes|
|```k = r_cleardecals```|Clears blood splatter / bullets|


## Bind Help
### Weapon slots
|Console command|Purpose|
|:-|:-|
|```slot1```|Primary|
|```slot2```|Secondary|
|```slot3```|Knife|
|```slot4```|Cycle Grenades (left to right)|
|```slot5```|Bomb|
|```slot6```|HE Grenade|
|```slot7```|Flashbang|
|```slot8```|Smoke Grenade|
|```slot9```|Decoy Grenade|
|```slot10```| Incendiary Grenade|
|```slot11```| Zeus|

<!--
### Ninja / Bomb Finder
```bind "key" "toggle gameinstructor_enable"```
```bindtoggle "key" "gameinstructor_enable 0 1"```
-->

## Useful Links
Key codes for Keyboard Binds
[CSGO Binds Generator](http://csgobindsgenerator.com/)

Steam Guide for Scripts, Binds and Configs
[How to: Scripting, Binds and Configs](https://steamcommunity.com/sharedfiles/filedetails/?id=314801693)

## Updates / Experimental
### Considerations
- Numpad as buy scripts
- Alt aliases for grenades (Alt+1 = HE, Alt+2 = Flashbang etc.)
- Jump throw
- Crouch throw
- Crouch Jump for strafing (as suggested by [fstr])
- Clutch mode which notifies team when muted / unmuted
- Game instructor (like toggleVoice to allow for a message to appear in developer 1)

## Sources
|Content|Source|
|:-|:-|
|Game Volume|[Gatlin Newhouse/CSGO-configs][]|

## Extras
Gist used in index.html
[Gist: autoexec.cfg](https://gist.github.com/albyp/1045efe61a192de993962a7a4c62680e#file-autoexec-cfg)

<!-- Links -->
[Gatlin Newhouse/CSGO-configs]: https://github.com/gatlinnewhouse/CSGO-configs/
[Gist: autoexec.cfg]: https://gist.github.com/albyp/1045efe61a192de993962a7a4c62680e#file-autoexec-cfg
[RAW: autoexec.cfg]: https://raw.githubusercontent.com/albyp/cs-conf/master/autoexec.cfg


<!-- Steam Accounts -->
[fstr]: http://steamcommunity.com/profiles/76561198104710099
