
 <!-- What I need to add -- StackEdit to see how the README looks like -->
<!--  -->
 <!-- Screenshot/gif for "Easy method for finding this data" -->
 <!-- Contents table for README -->


# CS:GO Config - alby
<!-- Add issues etc. -->

## Installation & Usage
C:\Program Files\Steam\userdata[your Steam ID]\730\local\cfg\
>**Note:** this is wherever Steam was installed (may not necessarily be C:\Program Files)

Easy method for finding this data
- Open Steam App
- Library | Right-click CS:GO
- Properties | Local Files | Browse Local Files...
- csgo\cfg
>**Note:** This installation assumes that the *.cfg file is named ```autoexec.cfg```


### Adding the config to launch
- Library | Right-click CS:GO
- Properties | Set Launch Options
- ```+exec autoexec.cfg```


### Launch Options
Quick copy
```-high -novid -tickrate 128 -console -developer 1 +exec autoexec.cfg```

|Parameter|Purpose|
|-|-|
|```-high```|Sets game to high priority in Task Manager|
|```-novid```|Ignore videos on open|
|```-tickrate 128```|Sets default update rate to 128 tick, will switch to 64 for comp/casual|
|```-noborder```|Removes windowed borderless|
|```-w 1920 -h 1080```|Resolution|
|```-console```|Opens console immediately after launching the game|
|```-developer 1```|Console set to developer (better console)|
|```-insecure```|For testing the goods (no VAC)|
>Note: Remember to add ```+exec autoexec.cfg```
___
## Bind Help
### Weapon slots
|Console command|Purpose
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

### Ninja / Bomb Finder
```bind "key" "toggle gameinstructor_enable"```
```bindtoggle "key" "gameinstructor_enable 0 1"```

## Useful Links
Key codes for Keyboard Binds
[CSGO Binds Generator](http://csgobindsgenerator.com/)

Steam Guide for Scripts, Binds and Configs
[How to: Scripting, Binds and Configs](https://steamcommunity.com/sharedfiles/filedetails/?id=314801693)

## Updates / Experimental
- Currently testing CounterStrafe Assistant from [Gatlin Newhouse]
### Things to consider binding
- Numpad as buy scripts
- Alt aliases for grenades (Alt+1 = HE, Alt+2 = Flashbang etc.)
- Jump throw
- Crouch throw
- Clutch mode which notifies team when muted / unmuted

## Sources
|Content|Source|
|:-|:-|
|Game Volume|[Gatlin Newhouse/CSGO-configs][]|

## Extras
Gist used in index.html
[Gist: autoexec.cfg](https://gist.github.com/albyp/1045efe61a192de993962a7a4c62680e#file-autoexec-cfg)

<!-- Links -->
[Gatlin Newhouse/CSGO-configs]: https://github.com/gatlinnewhouse/CSGO-configs/
