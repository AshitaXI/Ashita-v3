**Author:** [Sjshovan (Apogee)](https://github.com/Ap0gee)  
**Version:** v0.9.0  


# Mount Muzzle

> An Ashita v3 addon that allows the user to change or remove the default mount music in Final Fantasy 11 Online.


### Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Aliases](#aliases)
- [Usage](#usage)
- [Commands](#commands)
- [Support](#support)
- [Change Log](#change-log)
- [Known Issues](#known-issues)
- [TODOs](#todos)
- [License](#license)

___
### Prerequisites
1. [Final Fantasy 11 Online](http://www.playonline.com/ff11us/index.shtml)
2. [Ashita v3](https://www.ashitaxi.com/)

___
### Installation

**Ashita:**   
1. Navigate to the `Addons` section on the left.
2. Locate the `MountMuzzle` addon.
3. Click the flashing download button near the upper-right corner.

**Manual:**
1. Navigate to <https://github.com/Ap0gee/Ashita-MountMuzzle>.
2. Click on `Releases`. 
3. Click on the `Source code (zip)` link within the latest release to download.
4. Extract the zipped folder to `Ashita_v3/addons/`.
5. Rename the folder to remove the version tag (`-v0.9.0`). The folder should be named `MountMuzzle`.

**Autoloading:**   

By default you will need to manually load this addon each time you restart the game.
To autoload MountMuzzle so that it is always ready for use upon entering the game, follow these steps:

1. Navigate to the `Ashita_v3/scripts/` directory.
2. Open the `Default.txt` file.
3. Locate the `Load Common Addons` section.
4. add the following line: `/addon load mountmuzzle`.

___
### Aliases
The following aliases are available to Mount Muzzle commands:    

**mountmuzzle:** muzzle | mm  
**list:** l     
**set:** s  
**get:** g  
**default:** d  
**unload:** u  
**reload:** r  
**about:** a  
**silent:** s  
**mount:** m   
**chocobo:** c  
**zone:** z    
**help:** h  
 
 ___
### Usage

Manually load the addon by using the following command:
    
    /addon load mountmuzzle  
    
___    
### Commands

**help**

Displays available Mount Muzzle commands. Below are the equivalent ways of calling the command:

    /mountmuzzle help
    /muzzle help
    /mm help
    /mountmuzzle h
    /muzzle h
    /mm h

**list** 

Displays the available muzzle types. Below are the equivalent ways of calling the command:

    /mountmuzzle list
    /muzzle list
    /mm list
    /mm l
   
**set _\<muzzle>_**

Sets the current muzzle to the given muzzle type. This command takes a single argument represented by `<muzzle>`. Below are the equivalent ways of calling the command:

    /mountmuzzle set <muzzle>
    /muzzle set <muzzle>
    /mm set <muzzle>
    /mm s <muzzle>
    
Here are some usage examples for the **set _\<muzzle>_** command: `mm set silent` and `muzzle set zone` etc...

**get**

Displays the current muzzle that is set. Below are the equivalent ways of calling the command:
    
    /mountmuzzle get
    /muzzle get
    /mm get
    /mm g
    
**default**

Sets the current muzzle to the default muzzle type: `Silent`. Below are the equivalent ways of calling the command:

    /mountmuzzle default
    /muzzle default
    /mm default
    /mm d
    
**unload**

Unloads the Mount Muzzle addon. Below are the equivalent ways of calling the command:
    
    /mountmuzzle unload
    /muzzle unload
    /mm unload
    /mm u
    
**reload**

Reloads the Mount Muzzle addon. Below are the equivalent ways of calling the command:
    
    /mountmuzzle reload
    /muzzle reload
    /mm reload
    /mm r

**about**

Displays information about the Mount Muzzle addon. Below are the equivalent ways of calling the command:
    
    /mountmuzzle about
    /muzzle about
    /mm about
    /mm a
    
___
### Support
**Having Issues with this addon?**
* Please let me know [here](https://github.com/Ap0gee/Ashita-MountMuzzle/issues/new).
  
**Have something to say?**
* Send me some feedback here: <sjshovan@gmail.com>

**Want to stay in the loop with my work?**
* You can follow me at: <https://twitter.com/Sjshovan>

**Want to show your love and help me make more awesome stuff?**
* You can do so here: <https://www.paypal.me/Sjshovan>  

___
### Change Log

**v0.9.0** - 12/4/2018
- Initial release

___
### Known Issues

- **Issue:** If Mount Muzzle is selected to automatically load and the player is mounted upon login, there is a significant delay before the chosen music will begin to play.
- **Issue:** Upon changing zones the default music can be heard for a moment before the chosen music begins to play.
- **Issue:** Unable to correctly set mount music to original if Mount Muzzle is unloaded while mounted. 

___    
### TODOs

- **TODO:** Investigate alternative methods for music change as packet injection/swap allows the player to hear the default music upon zone change and login, regardless of chosen music.
- **TODO:** Investigate methods for determining which mount type the player is on when loading/unloading Mount Muzzle.
___

### License

Copyright © 2018, [Sjshovan (Apogee)](https://github.com/Ap0gee).
Released under the [BSD License](LICENSE).

***