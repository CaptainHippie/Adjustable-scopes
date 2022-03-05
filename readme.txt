===ADJUSTABLE SCOPE VIEW 1.8===

Conflicts and risks: 
Important: If you're using blindsides reanimtions, this must be installed only after blindsides reanim or the best option is follow the exact load order in EFT alternate sights mod description. Its a QoL script which only modifies hud_fov values under conditions so you're safe and you can add/remove it anytime

Installation
Easy, just copy gamedata folder to game folder but I recommend using MO2 for any anomaly addon installation
It is independant of most addons but in case of conflicts make sure to follow load order from EFT reposition addon descrition. For example, if you're using blindsides reanimtions, this must be installed only after blindsides reanim

What the mod does :
1. This doesn't change hands position in any way, so feel free to use alongside any weapon reposition addons, EFT reposition is the one most upto date
2. All 2D scopes are exempt from any changes since they are nothing more than texture overlays
3. Dynamically change how far you hold the weapon by keybinds (you need to have MCM installed to enable this option. Default key (Shift + num-) to bring it closer and (Shift + num+) to bring it farther .Keybinds are fully customizable via MCM. And to reset the current weapon's setting back to default, press backspace (default key) while holding the gun. All keybinds are customizable via MCM.
4. By default, it brings the ironsights a little closer, the scopes and collimators are slightly more closer, I thought it was necessary. And special category of scopes(currently ACOG and Susat) have a 3rd value because by default they were way too far away due to the game's technical limitations. This brings them much closer together, I put them on a different slider so as to not make the other scopes do the same
5. You can give custom values to any weapon and its scoped variants by editing/adding an ltx, without any conflicts. (bit older feature, may not be useful after new update)
6. Note that the alternate aim sights for BaS and vanilla guns follow sliders depending on weapon attachments. Putting a different slider for alternate sights is more complicated, and I would probably look into it later
7. Grenade lauchers and pistols also gets a unique slider after latest update

Changelog :
1.8 - Improved Russian translation thanks to EverybodyLies#9816 on anomaly discord. Also a little bit of script cleanup
1.7 -Major update. Refactored majority of the code, added ability to dynamically adjust zoom hud fov on the fly using keybinds configurable via MCM. Also added sliders for pistols and enabled wildcard loading for custom ltx files
1.6 - fixed a bug where the zoomed in hud fov will be saved upon death or loading save. Also made an exception for when pistols are used with devices
1.5 hotfix - fixed Russian translation thanks to xcvb and haruwu
1.5 - fixed a bug which was treating SMGs as pistols
1.4.1 hotfix - fixing a couple of bugs I made accidentally
v1.4 - Fixed hud fov resetting, added grenade launcher slider, added russian translation and made exception for pistols with attachments
v1.3 - Alternate sights(only for the 2D scopes) will ignore the 3rd slider(intended for BaS), changed default values
v1.2 - Added full customizability, and the values are inside an ltx for easier access. You can give custom hud_fov values for any weapon and their scoped variants in a conflict free manner
v1.1 - Added method to change the sliders for specific guns

Credits:
HarukaSai for the original idea and script which I only modified :)
Ravenascendant, Ishmaeel and others for helping further
Cr3pis for the awesome showcase video