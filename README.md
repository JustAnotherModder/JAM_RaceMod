# JAM_RaceMod
A streetrace mod. Choose your destination by setting a waypoint, challenge nearby players (including wagering if you choose) and race them to the finish line. Winner takes all.

### Requirements
* [JAM_Base](https://github.com/JustAnotherModder/JAM)
* [JAM_Notify](https://github.com/JustAnotherModder/JAM_Notify)

## Download & Installation
- Download https://github.com/JustAnotherModder/JAM_RaceMod/archive/master.zip
- Extract the JAM_RaceMod folder (and its contents) into your `JAM` folder, inside of your `resources` directory.
- Open `__resource.lua` in your `JAM` folder.
- Add the `JAM_RaceMod` files to their respective locations, like so :

```
client_scripts {
	'JAM_Main.lua',
	'JAM_Client.lua',
	'JAM_Utilities.lua',

	-- RaceMod
	'JAM_RaceMod/JAM_RaceMod_Config.lua',
	'JAM_RaceMod/JAM_RaceMod_Client.lua',
}

server_scripts {	
	'JAM_Main.lua',
	'JAM_Server.lua',
	'JAM_Utilities.lua',

	-- MySQL
	'@mysql-async/lib/MySQL.lua',

	-- SafeCracker
	'JAM_RaceMod/JAM_RaceMod_Config.lua',
	'JAM_RaceMod/JAM_RaceMod_Server.lua',
}
```
