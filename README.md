
# dotfiles
*keep it simple, stupid.*


my dotfiles for arch linux

notes:
1) this was compiled using [chezmoi](https://github.com/twpayne/chezmoi). This makes it pretty easy to pull and apply using chezmoi's update command. However, it may look a little weird with all the "dot_"s and "executable_"s. Just replace "dot_" with "."s and remove any "executable_" tags if you're not interested in using chezmoi. I do like it though, and I've written a [little script](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_chezmoi_update) to help keep them up to date.
2) I have shamelessly taken most of my dots from Luke Smith's [voidrice](https://github.com/LukeSmithxyz/voidrice). There are some small improvements I have made, but at the core, it's mostly his.

quick rc's:

[vimrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/nvim/init.vim)

[dunstrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/dunst/dunstrc)

[zshrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/zsh/dot_zshrc)

[xinitrc](https://github.com/at-manos/dotfiles/blob/master/dot_config/xinitrc)

[zprofile](https://github.com/at-manos/dotfiles/blob/master/dot_zprofile)

[xprofile](https://github.com/at-manos/dotfiles/blob/master/executable_dot_xprofile)


cool scripts:
	1) [crowmenu](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_crowmenu): Translator using crow, dmenu, and dunst. OC.
	2) [btmenu]()https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_btmenu: taken from [cdown/btmenu](https://github.com/cdown/btmenu) and added improvements.
	3) [nightNday](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_nightNday): will take sunset/sunrise data and set background accordingly if you have those files. OC.
	4) [booksplit](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_btmenu): Taken from [Luke Smith](https://github.com/LukeSmithxyz/voidrice/blob/master/.local/bin/booksplit). Will split albums/audiobooks/etc by a list of timecodes.
	5) [maimpick](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_maimpick): Taken from [Luke Smith](https://github.com/LukeSmithxyz/voidrice/blob/master/.local/bin/maimpick), again, however I've added an OCR option using [tesseract](https://github.com/tesseract-ocr/tesseract).

# screenies:

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
dunst notifications w/ [crowmenu translator](https://github.com/at-manos/dotfiles/blob/master/dot_local/bin/executable_crowmenu)
![snazzy af](https://github.com/at-manos/dotfiles/blob/master/screenshots/dunst.png?raw=true)
latest
![latest](https://github.com/at-manos/dotfiles/blob/master/screenie-latest.png?raw=true)
