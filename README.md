# My dotfiles for Arch Linux

## Install

Install dependencies
``` shell
sudo pacman -S neovim emacs qtile neofetch feh xcompmgr dmenu chromium zsh
```

And you also need install *oh-my-zsh*

Then clone my *config*
``` shell
git clone https://github.com/zerrari/dotfiles ~/config
mv .zshrc ~
mv .xinitrc ~
mv .config ~
```

## Usage

### Window Manager Qtile

I use *Alt* as my modkey,you can change it in `~/.config/qtile/config.py`,
The type `Alt`+`Shift`+`r` will restart the qtile and update the config.

### Editors

The details about the editors in my repos.
+ [Emacs](https://github.com/zerrari/.emacs.d)
+ [Nvim](https://github.com/zerrari/nvim)
