===ADJUSTABLE SCOPE VIEW 1.6===

Installation
Easy, just copy gamedata folder to game folder but I recommend using MO2 for any anomaly addon installation

Conflicts and risks: Just one file, must be installed before blindsides reanim or EFT alternate sights mod
IMPORTANT NOTES! : unfortunately the latest BaS has fixed hud_fov value in its weapon config files. So those weapons won't respond to any changes as until you go in and delete those lines :(
If you have problem with hud fov resetting, update addon to 1.4

What the mod does :
1. This doesn't change hands position in any way, so feel free to use alongside any weapon reposition addons
2. All 2D scopes are exempt from any changes since they are nothing more than texture overlays
3. Brings the ironsights a little closer. All the other 3D scopes are slightly more closer, I thought it was necessary.
   And special category of scopes(currently ACOG and Susat) have a 3rd value because by default they were way too far away 
   due to the game's technical limitations. This brings them much closer together, I put them on a different slider so as
   to not make other scopes do the same
4. After v1.2 update you can give custom values to any weapon and its scoped variants, without any conflicts
5. And of course, with MCM slider all these settings could be altered while playing :)
6. Note that the alternate aim sights for BaS and vanilla guns follow sliders depending on weapon attachments.
   Putting a different slider for alternate sights is more complicated, and I would probably look into it later
7. Grenade lauchers has a unique slider after 1.4 update

Changelog :
1.6 - fixed a bug where the zoomed in hud fov will be saved upon death or loading save. Also made an exception for when pistols are used with devices
1.5 hotfix - fixed Russian translation thanks to xcvb and haruwu
1.5 - fixed a bug which was treating SMGs as pistols
1.4.1 hotfix - fixing a couple of bugs I made accidentally
v1.4 - Fixed hud fov resetting, added grenade launcher slider, added russian translation and made exception for pistols with attachments
v1.3 - Alternate sights(only for the 2D scopes) will ignore the 3rd slider(intended for BaS), changed default values
v1.2 - Added full customizability, and the values are inside an ltx for easier access. You can give custom hud_fov values for any weapon and their scoped variants in a conflict free manner
v1.1 - Added method to change the sliders for specific guns

Customization guide :
to avoid confusion I've provided an example config so you can refer
1) open weapon_fov_values.ltx inside gamedata/configs/items
2) Add/remove scopes under the section [bad_scopes], these are the scopes that follows the 3rd slider
3) If you want to give a custom hud_fov to a weapon with integrated sights, add the weapons section name under [] and use iron = value   (integrated 3D scopes follow value for ironsights) 
4) For giving a custom hud_fov to a multiscope weapon, add the weapons section name under [] and use scope_name = value   (you can find the correct scope name under the weapon's ltx) 
be sure to refer to the correct weapon and scope section IDs from their ltx

Credits:
HarukaSai for the original idea and script which I only modified :)
Ravenascendant, Ishmaeel and others for helping further