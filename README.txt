Hey there!

What you have right now is a version of Blockland v20 for Mac pieced back together and ready to play!
The v20 Mac binary was found on Friday, December 1st, 2017.

To play the game, run "run.command"; or to run a dedicated or dedicated LAN server, run either "dedicated.command" or "dedicatedLAN.command".
"Technical" info if you're into that stuff:

- the v20 Mac binary was downloaded off cloud.blockland.us; it's still on the servers
  - the blob hash should be f5797c4decac42976c93ea87e58f882ed2a729d7
- the base scripts are taken from v19 Mac
  - the dso version v20 Mac seems to be looking for is 190, which is basically v19
- this was tested on macOS High Sierra 10.13
  - the game should work on whatever version you're using though
- the .app reads version 19m, I didn't bother updating the Info.plist
  - the game itself still is v20
- no, BlocklandLoader v20 will not work with v20 Mac, that only works for Windows
- i've also provided Script_CustomMS (credit goes to Clay Hanson) because hosting on the actual master server on an older version can earn you a revoke

[UPDATE: MARCH 2ND, 2018]
+ added Map_SFix (edit of the Slopes map that fixes discolored textures, credit to Heedicalking)
+ added default save folders for Bedroom, Kitchen & Slate (forgot to add those in when I was making this, whoops)
+ added ADD_ON_LIST.cs and colorSet.txt to config/server (default stuff)
- removed Bot, DayCycle, Gamemode, Ground, Sky, SpeedKart, and Water add-ons (they only work in v21 so they're not necessary, also they were somewhat making the dmg size big)
- removed latestManifest.dat (we're not using the launcher, lol)
- removed Map_SewerSystem (I left that in there when I was initially testing the v20 Mac binary)
- removed hats folder in base (unnecessary)
- removed crapOns_Cache.cs (i have no idea if that was supposed to be there)
- removed thumbnail images for images in base/lighting (those only work in v21 for the environment settings)

Cheers,
- Ahead (ID: 33159)
