![Super Volito Tile Banner](https://supervolito.netlify.com/images/BannerMain.png)

# Project Goals:
* Create an example in html5 for promotion of the exe version.
* Keep file download size under 200mb.
* Create an expirence that most compputer can handle (low frame lantency [30-50 fps])
* Add Multiplayer for future use in other games/demos.

# Status: Suspended

## Feburary 26, 2020 - Lap Times Update
* Features
  * Added existing code for lap timer and Checkpoints
  * Added Background models for enviroment imrpovement
  * Added subsurf and smooth verts to craft for better lighting
  * Added production level lighting
  * Added better compression algorithm To reduce download size
  
* Bug Fixes
  * Fixed various Blur bugs from last version
  * Added new shader to craft to improve stats visiblity
  * Fixed floating track piece causing player to crash into
  * Removed Crashing sensitivity for later improved damage system
  * Added "R" to kill craft (miss emplimentation in last release)
  * Added bounding sphere to avoid flying infinately. Thanx @Mauircio Degregori
  * Fixed Lighting but where seems of track where causing bad shaddows on lightmap
  
* Known Bugs
  * Craft can some times get stuck to the ground
  * Craft pings over Rails uncrontrollable
  * Controls explaination is absent and confuses users Thanks @Nick Migel
  * Craft info dump can some times be hard to read based on lighting
  * Some track peices still have shadoing errors, will need to remove all faces on Sides to stop double facing mesh
  
## Febuary 22, 2020 - Hot fix IndexDB
* Added IndexDB suport so you only have to download once

## Febuary 21 2020 - Inital Commit + Styling
* Features 
  * Base push of the game
  * Added css and styleing
  * Added various fixes to the js
  * Fixed html to fix various unneeded buttons
* Known Bugs
  * Lighting is not built
  * Track is hard to navigate
  * Checkpoint system was not correctly added
  * Kill craft button doesnt work even though it was expected to
  * Needs suport for saving download
  * Needs better compression

# Credits
  Chase Wenner
  Valknor (Chris)
  Leviscus Tempris (James)
  
### Specail Thanks
  * Walciony - For Music help
  * Awol - For Model tips and Animation Suport
  * Sniper Goth - For Model tips and Uv help
  * WatisDeze - For Coding suport
  #### Core Game Testers
  Captain Chronic.
  Alhoprod,
  Asian Man Tran,
  Auios,
  MarshallOutlaw,
  Rainee,
  Crisprlexi,
  Mauircio Degregori,
  Nick Migel,
  And Many Others
