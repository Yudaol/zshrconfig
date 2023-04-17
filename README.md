# zshrconfig
my .zshrc config to have the terminal like kali linux


# for install :

# mac with port (macport, you can download at https://www.macports.org/install.php)

`sudo port install zsh zsh-syntax-highlighting zsh-autosuggestions`

now press tape in the terminal `zsh`

you will have a text message with 3 option press `0`

next you will need to delete the .zshrc file for create a new one

`rm .zshrc`

then copy the zshrc I make and past it into your personnal folder /Users/...

then we need to rename the zshrc into .zshrc

`cp zshrc .zshrc`

then you can change the default login shell :

`chsh -s /bin/zsh`

then change the default terminal look :

`source .zshrc`

If you have message : last login ...

you can tape :

`touch .hushlogin`

# Linux (ubuntu,...)

`sudo apt update`

`sudo apt upgrade`

`sudo apt install zsh`

`zsh`

press `0`

`sudo apt install zsh-syntax-highlighting zsh-autosuggestions`

`chsh -s /bin/zsh`

copy the zshrc in your folder and rename it

rename :

`cp zshrc .zshrc`

`source .zshrc`










the source of the project (you can find in this website more information and some look for linux (gnome-tweaks with kali-dark):

`https://linuxopsys.com/topics/make-ubuntu-terminal-look-like-kali-linux`




