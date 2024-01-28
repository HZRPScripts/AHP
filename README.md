# | AutoHoodPop | v.1.2.2 (Public Release)
![Released January 2022](https://img.shields.io/badge/release%20date-January%202022-purple)
![1.2.0](https://raster.shields.io/badge/version-v1.2.2-blue)
![moonloader](https://img.shields.io/badge/lua-moonloader-orange)
![MIT License](https://img.shields.io/badge/license-MIT-green)
![Requires: sampfuncs, moonloader, inicfg](https://img.shields.io/badge/requires-sampfuncs%20|%20moonloader%20|%20inicfg-red)


**| AutoHoodPop |** is a GTA:SA Moonloader modification that automatically opens your car hood at a specified HP. The health "***danger zone***" is defaulted to 400 on first launch and can be changed and saved permanently by the user. It handles all types of vehicles so if you are in a vehicle that does not require [/car hood] you will get a "Repair Needed" notification only.

## Requirements
- inicfg
- Moonloader
- Sampfuncs
- **[/pagesize 15]** or higher for display of the **[/ahphelp]** menu
  - ***Note: Don't wanna do this? Fine! - Use*** **[/ahpmini]**

## Installation
Download the .lua file and place it inside the "moonloader" folder located in your GTA:SA Install Folder. The first time you launch GTA:SA a configuration directory and file will be created for the modification.

### Modification File & Folder Structure
```
moonloader
  -AutoHoodPop.lua
  -config
      --Masaharu's Config
          ---AutoHoodPop.ini
```

***Note: README.md is not required for the modification to work.***

## Usage
**| AutoHoodPop |** is automatically enabled when initially installed. It can be disabled using **[/ahp]**. You can set the health to pop the hood by using **[/ahphealth]**. All settings are permanently saved to a configuration file.

```
/ahp - Enable/Disable | AutoHoodPop |
/ahphelp - Show the help menu.
/ahpmini - Show the mini help menu.
/ahphealth - Set health hood will open at. E.g. [/ahphealth 350]
```

- **[/ahphealth]** - Allowed Health Range - 250 HP -> 999 HP

### Special Thanks
- [Brad Ringer](https://forums.hzgaming.net/member.php/34885-Brad-Ringer) - Consulting & Boilerplate Only - No Script Use/Design/Implementation/Legal Responsibility or Involvement
