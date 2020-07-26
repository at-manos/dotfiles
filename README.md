
# dotfiles
*keep it simple, stupid.*


my dotfiles for arch linux

notes:
-  this was compiled using [chezmoi](https://github.com/twpayne/chezmoi). This makes it super easy to pull and apply these dots.
	- chezmoi init https://github.com/at-manos/dotfiles.git
	- chezmoi diff (if you want to see what changes it'd make)
	- chezmoi apply
- However, it may look a little weird with all the "dot_"s and "executable_"s if you don't want to use chezmoi. Just replace "dot_" with "."s and remove any "executable_" tags if you're not interested in using it. I do like it though, and I've written a [little script](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_chezmoi_update) to help keep them up to date.
-  I have shamelessly taken most of my dots from Luke Smith's [voidrice](https://github.com/LukeSmithxyz/voidrice). There are improvements I have made, but at the core, it's mostly his.

quick rc's:

- [vimrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/nvim/init.vim)

- [dunstrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/dunst/dunstrc)

- [zshrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/zsh/dot_zshrc)

- [xinitrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/xinitrc)

- [zprofile](https://github.com/at-manos/dotfiles/blob/master/dot_zprofile)

- [xprofile](https://github.com/at-manos/dotfiles/blob/master/executable_dot_xprofile)

quick info:



| Name      | Function        | Notes                                                                                                                                                                |
|-----------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| dwm       | Window Manager  | [Luke Smith's build of dwm](https://github.com/LukeSmithxyz/dwm) with some slight modifications.                                                                     |
| dmenu     | Dynamic Menu    | Suckless menu program. [More here](https://wiki.archlinux.org/index.php/Dmenu)                                                                                       |
| picom     | Compositor      | Good customizable compositing. [More here.](https://wiki.archlinux.org/index.php/Picom)                                                                              |
| zsh       | Shell           | Really nice shell. [More here](https://wiki.archlinux.org/index.php/Zsh)                                                                                             |
| nvim      | Editor          | [Neovim](https://github.com/neovim/neovim) with several plugins. Check .config/nvim for list of plugins.                                                             |
| zathura   | Document Viewer | Good document viewer with vim-keys integrated. [More here.](https://wiki.archlinux.org/index.php/Zathura)                                                            |
| st        | Terminal        | [Luke Smith's build of st](https://github.com/LukeSmithxyz/st)                                                                                                       |
| brave     | Browser         | I would generally use firefox, however, playerctl works really well with chromium-based browsers.                                                                    |
| dunst     | Notifications   | Simple and clean. [More here.](https://wiki.archlinux.org/index.php/Dunst)                                                                                           |
| mpv       | Media Player    | Classic. [More here](https://wiki.archlinux.org/index.php/Mpv)                                                                                                       |
| playerctl | Media Controls  | Allows you to control multiple different types of audio sources, e.g spotify, chromium, mpv, etc. Really nice. [More here.](https://github.com/altdesktop/playerctl) |
| sxiv      | Image Viewer    | [Simple X Image Viewer](https://github.com/muennich/sxiv). Very versatile, and supports gifs.                                                                        |
| sddm      | Display Manager | [Simple Desktop Display Manager](https://wiki.archlinux.org/index.php/SDDM). Nice aerial video shots on login screen. Looks very clean.                              |

cool scripts:
-  [crowmenu](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_crowmenu): Translator using crow, dmenu, and dunst. OC.

-  [btmenu](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_btmenu): Dmenu based menu for controlling bluetooth devices. Taken from [cdown/btmenu](https://github.com/cdown/btmenu) and added improvements.


-  [booksplit](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_btmenu): Will split albums/audiobooks/etc by a list of timecodes. Taken from [Luke Smith](https://github.com/LukeSmithxyz/voidrice/blob/master/.local/bin/booksplit).

-  [maimpick](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_maimpick): Dmenu based screenshot menu for maim. Taken from [Luke Smith](https://github.com/LukeSmithxyz/voidrice/blob/master/.local/bin/maimpick), again, however I've added an OCR option using [tesseract](https://github.com/tesseract-ocr/tesseract).
- [setbganimated](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_setbganimated): Very simple animated backgrounds using xwinwrap. Set up for 1920x1080 displays, however that's easily changable.


# screenies:
[*old bg*](https://github.com/at-manos/dotfiles/blob/master/walls/old.png)

[*new bg*](https://github.com/at-manos/dotfiles/blob/master/walls/current.png)

blank
![blank af](https://github.com/at-manos/dotfiles/blob/master/screenshots/blank.png?raw=true)
archey
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/archey.png?raw=true)
spotify-tui
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/spt.png?raw=true)
cava
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/cava.png?raw=true)
looking busy(nvim, btm, cava)
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/busy.png?raw=true)
zathura(book: The C Programming Language)
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/zathura.png?raw=true)

dunst notifications w/ [crowmenu translator](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_crowmenu)
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/dunst.png?raw=true)
latest
![latest](https://github.com/at-manos/dotfiles/blob/master/screenie-latest.png?raw=true)
