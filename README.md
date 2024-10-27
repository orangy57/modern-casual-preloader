# Modern Casual Preloader

This preloader is configured to load every model I could realistically think of or have seen mods of, 
if anything is missing please leave a comment on gamebanana.

CREDITS: Special thanks to Skyrym, Fedora31, treacherousfiend, dweeb, A Paint Bucket Named Huey, 
Panic Civilian, and Flpstrike for their work and help on this project.
Shoutouts to washipato and wiseguy149 for making tr_walkway, and huge thanks to hamn 
for updating tr_walkway to use VScript!! 

--------------------------------------------------------------------------------------
TO INSTALL: 
Drag this stuff into your Team Fortress 2/tf/custom folder and add +exec preloader.cfg 
to your launch options in Steam.
Alternatively, you can use +exec preloaderwalkway.cfg to launch the game in tr_walkway.
--------------------------------------------------------------------------------------

Extra modding notes for newbies:
	-Mods take priority by alphabetical order. A mod named Amymod.vpk will load on top of a mod named Zmymod.vpk
	-Some mods come in folders instead of .vpks, these folders need to be installed correctly for mods to load.
		-Clicking through the folders should look like: Team Fortress 2/tf/custom/cool mod/
			There is usually a folder called "models" and/or "materials" inside the "cool mod" folder
			Make sure your folders *DONT* look like: Team Fortress 2/tf/custom/cool mod/cool mod/ or else they won't load.
	-Particle mods (toon FX, etc.) won't work in Casual

"Will this get me VAC banned?" No. This preloader doesn't use any hacks or injects.

Have fun!
-pilso


KNOWN BUGS: 
-Saxton Hale mods reset if you join any map that isn't VSH
-Long startup time, if game stops responding click "wait for this program to respond"
-MvM Victory screen is gray and doesn't work sometimes, type hud_reloadscheme while playing MvM to fix
-Mysterious and elusive missing eyes bug that causes severe lag, trying running the .Cache Cleaner.bat