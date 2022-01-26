# Arch Linux Rice

Config files of my arch rice. Just copy the files to the following directories.

## Make Dmenu

<b>Requirements</b> : XLib header files.

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
------------------------------------------------
