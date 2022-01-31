# Arch Linux Rice

Config files of my arch rice. Just copy the files to the following directories.

![Desktop](https://github.com/KngKong/Arch-config/blob/master/screenshots/desktop.jpg)

## Dmenu

<b>Requirements</b> : XLib header files.

![Dmenu](https://github.com/KngKong/Arch-config/blob/master/screenshots/dmenu.png)

<b>Pathces Included</b>  
* Case insensitive <br /> 
* Fuzzy match <br />      
* Fuzzy highlight  <br />  
* Mouse support <br />    
* Border <br />           
* Line height <br />     
* High priority <br />    
* Numbers <br />   
* And Some color changes...

Use `sudo make clean install` to install dmenu to all users or edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

## Nvim config

<b>Requirements</b> : Neovim(ofcource you need neovim) and vim-plug.

Use this config or use your existing .vimrc by sourcing it to neovim config.
Just replace the `inti.vim` file with this,
```
    set runtimepath^=~/.vim runtimepath+=~/.vim/after
    let &packpath = &runtimepath
    source ~/.vimrc
```

## Bashrc

<b>Requirements</b> : bash-completion (for autocompletion)

### Sources

Polybar & Xresources : [@ManuLosta/dotfiles](https://github.com/ManuLosta/dotfiles)\
Powerline Fonts : [@powerline/fonts](https://github.com/powerline/fonts)\
Bashrc : [@gentoo-bashrc](https://aur.archlinux.org/packages/gentoo-bashrc/)

------------------------------------------------
