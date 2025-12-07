SilentPatch 1.1 for GTA VC
Build 9
Last update - 22.09.2019


DESCRIPTION

	GTA VC is a great game, but it possesses some issues. This small plugin addresses several of these.
	It focuses mainly on fixing bugs present on PC, but not on PS2 version of the game.

	Fixes featured in this plugin:

	* Fixed an issue where installing the game on A or B drive made the game ask for the CD
	* Mouse should not lock up randomly when exiting the menu on newer systems anymore
	* Mouse will not go beyond the game rect now, allowing to play the game on multimonitor setups without problems
	* Mouse vertical axis sensitivity now matches horizontal axis sensitivity
	* Mouse vertical axis does not lock during camera fadeins now
	* More precise frame limiter, reducing lag spikes a bit when playing with Frame Limiter on
	* Rosenberg's lines which play when player is Busted work correctly now (just like with Rosie's Audio Fix)
	* Game now performs a bit better on high FPS. It doesn't freeze on fadeouts anymore, although it still has issues
	  with car physics, gravity and sounds. Therefore it's still recommended to play with Frame Limiter set to ON
	* Wet road reflections render properly again (just like with Road Reflections Fix)
	* Reintroduced light glows under weapon/health/armour pickups, bribes, hidden packages and money pickups - they
	  showed only on PS2 due to a bug in all PC versions
	* All texts now have proper shadows (depending on chosen resolution, without the fix they'd appear thinner etc.
	* Free resprays will not carry on a New Game now
	* Fixed ambulance and firetruck dispatch timers - they reset on New Game now
	* Corrected crime codes for police dispatch audio - police dispatch now refers to player crimes correctly
	* Fixed a bug causing cheat-spawned melee weapons to be forcibly replaced by other melee weapons upon walking into
	  a pickup
	* FILE_FLAG_NO_BUFFERING flag has been removed from IMG reading functions - speeding up streaming
	* Alt+F4 now works properly
	* Some car panels now are detached after car's explosion (like they were meant to be but the code forcibly fixed
	  them immediately after damaging)
	* Metric-to-imperial conversion constants have been replaced with more accurate ones
	* Pathfinding for cars chasing the player has been improved
	* All censorships from German and French versions of the game have been removed
	* Bombs in cars stored in garages now save properly
	* Fixed an issue which would cause games to freeze if III/VC/SA were running at the same time
	* Car generator counters now work properly for generators with fixed amount of spawns
	* Extras on bikes now behave correctly, following bike lean and not floating in air
	* Keyboard input latency decreased by one frame
	* Made the game select metric/imperial units basing on system locale settings. This can be overridden from the INI
	  file
	* Some props in Malibu Club, Ocean View Hotel and Pole Position Club have been restored; more environment shows
	  outside when player is in interior too (just like on PS2)


INSTALLATION

	Easy as pie. Extract archive content to your VC directory (so SilentPatchVC.asi ends up
	in main game directory and map folders end up in 'data\maps') and that's all. Patches
	will take effect automatically.

	It is recommended to grab a ddraw.dll SilentPatch component together with this plugin!


SUPPORTED GAME VERSIONS

	* GTA VC 1.0 (all versions)
	* GTA VC 1.1 (all versions, including Steam and Rockstar Games Launcher versions)


SPECIAL THANKS

	People who helped to identify issues, tested the patch or were generally supportive:

	aap
	Ash_735
	Blackbird88
	iFarbod
	mirh
	Nick007J
	spaceeinstein
	ThirteenAG


CONTACT

	zdanio95@gmail.com - e-mail
	Silent#1222 - Discord

Subscribe to my YouTube channel for more footage from my mods!
https://www.youtube.com/user/CookiePLMonster

Follow my Twitter account to be up to all my mods updates!
http://twitter.com/__silent_

Also take a look at my blog, featuring modding and programming related articles and more!
https://cookieplmonster.github.io/
