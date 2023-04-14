# RE4 EFX Template
EFX 010 template for Resident Evil 4 Remake.

This is a beta release. Many structs have not been mapped for RE4 yet.

However, most of the structs have already been mapped for Monster Hunter Rise. It's just a case of deducing how the item enum has shifted.

The template will print an item type number when it runs into a struct that hasn't been mapped yet.

If the item type number is a sane number (<255), you just have to figure out what that number was on the [MHR EFX template](https://github.com/NSACloud/MHR-EFX-Template) and how it's been changed.

If you find out what any of the unknowns do, submit a pull request or an issue and I'll add the changes.

Be sure to change the character set to UTF-8 in View > Character Set or text will be garbled.

Read the template for notes. 

## EFX Color Change Script
![image](https://user-images.githubusercontent.com/46909075/232143830-d8a3bfac-7683-40b1-a830-99ce3a3a7e44.png)


![image](https://user-images.githubusercontent.com/46909075/213037217-9c32443a-156d-4b40-8204-98c98aaa8b95.png)

The **EFX_COLOR_CHANGE.1sc** script allows you to change the color of all entries in an EFX file. To use it, first install it under Scripts > View Install Scripts > Add.

Then with an EFX file open, run the script from the Scripts menu.

There are configurable options if you open the script file. You can enable or disable changing the colors of certain structs and also set the default colors.

The script is not intended to do all of the work. It will not work perfectly in all cases and you may have to manually tweak some things.

## Installation
Requires **[010 Editor](https://www.sweetscape.com/010editor/)**

Install the template under Templates > View Installed Templates > Add
