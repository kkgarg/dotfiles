# Dotfiles

## Steps for VIM Configurations

- Install dotfiles
```
$ cd ~
$ git clone https://github.com/kamalkgarg/dotfiles.git
```
- Install vundle
```
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
- Create symbolic link to ~/dotfiles/vimrc
```
$ ln -sf dotfiles/vimrc ~/.vimrc
```
- Open vim editor and execute :PluginInstall

You are done!

