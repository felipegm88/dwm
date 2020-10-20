# My dwm build

## Patches: 
+ alpha (for transparency)
+ attachaside (new clients appear in the stack rather than as the master)
+ cyclelayouts (cycles through the available layouts)
+ gridmode (adding a grid layout)
+ restartsig (allows dwm to be restarted with a keybinding)
+ rotatestack (moves a window through the stack, in either direction)
+ statuspadding (horizontal and vertical padding in the status bar are now configurable options)
+ uselessgap (adding gaps when more than one window)

## Dependencies
+ libxft
+ ttf-hack
+ ttf-joypixels
+ st
+ dmenu
+ tabbed

Also, you will need to add the following from the AUR:
+ nerd-fonts-complete (optional)
+ https://aur.archlinux.org/packages/libxft-bgra/ (needed for colored fonts and emojis)

	
## Installing dwm-distrotube on other Linux distributions

Download the source code from this repository or use a git clone:

	git clone https://gitlab.com/gorita/dwm.git
	cd dwm
    sudo make clean install
	
## Running dwm

If you do not use a login manager (such as lightdm) then you can add the following line to your .xinitrc to start dwm using startx:

    exec dwm
