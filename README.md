A custom keyboard inspired by Roland Kaufmann's Programmer Dvorak layout.

This rearranges the symbol keys to a percieved convenient location. Absolutely no science was used in the decisions.

I liked the idea of putting the numbers in the shift positions of the keys for programming but I kept the numbers on
the more common 1-0 layout for less confusion on my part.

For the Windows file edit using Microsoft Keyboard Layout Creator http://msdn.microsoft.com/en-us/goglobal/bb964665.aspx

#Installation

###Linux Console

gzip the keymap file and copy to /usr/share/kbd/keymaps/i386/dvorak/
Either use 'loadkeys dvorak_plusplus' or set the layout in your startup files

###X11 w/ xkb

Copy the dvk_pp file to /usr/share/X11/xkb/symbols
Set the XkbLayout to dvk_pp in your xorg config files

###Windows Install

Either install the Microsoft Keyboard Layout Creator and compile an install from the source file.

OR, grab a copy of the installer from the downloads section.