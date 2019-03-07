# VGSmartUnbuff

`Created by Threewords of the guild "Vanguard", Kronos, Twinstar`

This addon removes the lowest-priority buff every time when the number of buffs on the character has reached 30 (because stance and windfury AP bonus count towards the buff cap despite being hidden). So it effectively maintains the 29 buffs that have the highest priority based on the listed values inside the addon's `lua` file.

## Usage

* Current settings are tanking oriented.
* To change them, open the addon's `lua` file, and edit the contents of `VGSmartUnbuff_PriorityList` array.
* The lower the number next to a buff texture name is, the higher priority it has and the lower the chance that it will get removed.