# cstrike-cfg

My Counter-Strike: Source config I made for bhop and surf.

## Insalling

If you want to remove your config, delete any configs you may have in cstrike/custom and delete the cstrike/cfg folder. 
Then verify your game files using Steam.

Next, if you have Steam Cloud Synchronization enabled, make all the files in STEAM_FOLDER/userdata/USER_ID/240/remote/cfg blank. 
Do not delete them, or else Steam Cloud will redownload them. Alternatively, you can disable Steam Cloud.

Launch CSS with only "-novid -autoconfig -default -w 1920 -h 1080 +host_writeconfig config.cfg full +mat_savechanges +quit" launch options and run the game.

Afterwards, replace the launch options with "-insecure -novid -r_emulate_opengl -console" and paste in the new config files.

Launch Counter-Strike: Source with start.bat after downloading external programs.

## External programs:

https://github.com/b1scoito/bunnyhopfix/releases/tag/1.0

https://github.com/Haze1337/RawInput2/releases/tag/v1.1
