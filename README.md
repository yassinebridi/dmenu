# My build of dmenu

A list of stuff added to the original build of dmenu

- Hardcoded line height: 30, to be equal to polybar's
- Add a -w argument to add width
- Enable mouse click
- Map arrow keys to ctrl + hjkl
- Emoji support(Check my .dotfiles repo for the corresponding scripts)

To make changes to it:

- Make the needed changes
- run `make`
- then `sudo make clean install`

To uninstall it.

run `sudo make uninstall`
