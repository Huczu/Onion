# Onion (and Eggs) V3: Definitive Edition
#### A performant and straighforward retro gaming museum in your pocket.
### [Download newest release here](https://github.com/jimgraygit/Onion/releases)

<img src="https://user-images.githubusercontent.com/16885275/164891137-2bbdcfb5-e2c2-4658-8049-79b01d57dfed.png" width="948"> 

#### This release was made possible by Totofaki, Eggs, JimGray, Pixelshift, Shauninman and many more from the Onion community.

* [Installation](#installation) 
* [Features](#features)
* [Shortcuts](#shortcuts)

#### [Check also our wiki here](https://github.com/jimgraygit/Onion/wiki)

## Installation

#### Installation (Fresh Install):
- Format your SD card as Fat32. (Use a fast, trusted brand not the one sent with the handheld. The default miyoo SD card is slow, it will ruin your experience and likely loose your data)
- Unzip the ".tmp_update" folder and its content to the root of your SD.
- Boot up your Miyoo Mini and follow the on-screen instructions to get started.
- Your Mini will turn off after the installation is completed.
 (Don't delete the .tmp_update folder, it is now part of the Onion installation)  
- Copy your Bios files into the BIOS folder. 
  
#### Installation (Upgrade):
- Backup your saves, states and scraped images 
> - Saves and playtimes are located at /Retroarch/.retroarch/saves/_corename_
> - States are located at /Retroarch/.retroarch/states/_corename_
- Delete all folders from your SD except "BIOS" and "Roms"
- Unzip the ".tmp_update" folder to the root of your SD.
- Boot up your Miyoo Mini and follow the on-screen instructions to get started.
- Your Mini will turn off after the installation is completed.
 (Don't delete the .tmp_update folder, it is now part of the Onion installation)  
- Restore your backed up saves and states.
- Optional: To restore your box art, copy each system's box art folder into the system's respective folder in /Roms/ and rename each folder to "Imgs"

<img src="https://user-images.githubusercontent.com/16885275/164891118-efbcfc2e-bd25-4b88-8851-34862f550690.png" width="456">   
  
# Features

### Theme Switcher app / Custom themes  
<img src="https://user-images.githubusercontent.com/16885275/164838712-d45b3779-b30f-491c-b5ff-0bbc2a10865b.png" width="350"> 
<img src="https://user-images.githubusercontent.com/16885275/164838718-326f5590-96c2-4644-8fa2-1dd56f36a9bc.png" width="350"> 

Will come back soon :  
<img src="https://user-images.githubusercontent.com/16885275/154789504-84253d41-373d-4c84-b194-547c6343f904.png" width="350">  
  
- Preview and change themes on the fly, no reboot required.
- 26 themes from our community on this Github    

## Onion installer

<img src="https://user-images.githubusercontent.com/16885275/162589315-1d127c72-d404-4487-b379-3bde8179f566.png" width="350">  

- Install / uninstall only the systems and apps you need. Any action is reversible.
- Community presets, homebrews and more
   
### Play Activity 
<img src="https://user-images.githubusercontent.com/16885275/162589339-e779c6dd-4e9d-47f0-8543-4646d84fc748.png" width="350">  
- Track your game play times.   

### Onion Launcher
<img src="https://user-images.githubusercontent.com/16885275/164890313-c83dfc84-a684-416b-bd40-9f54c9f4e7db.png" width="350">  
 
The launcher is an user interface designed to be triggered when the miyoo mini starts.  
It allows you to launch the last game played in a few seconds, and with a simple press of a button to save your progression and turn off the console.   
It also allows you to quickly change games and many other advantages for a very simple experience :   
   
- Quick boot on your last game played.
- Quickly switch game from your history.
- Full overlay with accurate brightness, battery readings and playtimes.
- Improved brightness curve for better low-light gaming.
- Improved Sleep mode with full game suspension. (menu + power)
- Custom charging screen that prevent screen burnings.
- No more low bat flickering icon.
- No more memory leaks.
- Low bat (<10%) big visual battery warning indicator.
- Your handheld will also rumble periodically in game to indicate that your battery is bellow 10%
- When the battery goes < 4%, the game is now saved to prevent loosing progression, and the handheld turned off.


### RetroArch rebuilt from scratch
<img src="https://user-images.githubusercontent.com/16885275/154791260-d1a4d0b2-5582-45cc-a291-bead843a5171.png" width="350">  

- Compiled and partially rebuild by Eggs (Discord user no 968407509364772924) for precision and performance.   
    Custom audio driver.   
    Custom scalers.   
    New display driver.   
    New input driver.   
- Minimal input and audio lag.    
- Customs cores.    
- Finetuned with the best settings in mind.   
- Crisp 640*480 resolution.   
- Lag free.      
- Also a game launcher (Cores embedded, Playlists unlocked, Favorites unlocked)   
  
### Others  
- Many additional systems supported
- Experimental Arduboy support (Credit: JMARoeder)
- Updated PICO emulator to Fake08 standalone (Credit: Supergrom)
- Updated screenshot tool to v4 (Credit: eggs)
- Support for Icon Packs. Drag and drop your custom icons into the "Icons" folder at the root of your SD.
- Boxart moved to /Roms/_systemname_/Imgs for easier scraping
- Various bug fixes and optimizations.


### Shortcuts

<img src="https://user-images.githubusercontent.com/16885275/165266775-63e24f1b-d734-4eee-99c5-8bad502cd87e.png" width="500">  
  
Menu button : Exit Game  

Select + Start + R2 : Brightness up   
Select + Start + L2 : Brightness down  

Power button : Deep sleep    
Menu + Power : Light sleep   
   
Menu + Select : Retroarch menu     
   
Menu + R2 : Save state   
Menu + L2 : Load state   
   
Menu + R : Fast forward   
Menu + L : Rewind (If enabled)   
   
Menu + X : Toggle FPS display  
  
(In a Game boy game)  
R2/L2 : Change palette  

Other :
Force uninstall the launcher : start+select+menu+R2+L2


<img src="https://user-images.githubusercontent.com/16885275/164891039-665fffcf-b454-4b3c-87c6-13a92cb88a8b.png" width="500">   
