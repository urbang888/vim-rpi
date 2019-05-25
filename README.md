Vim on RPI
==========

Installation
------------

Install packages:
- vim

```
sudo apt install vim

curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
ln -s ~/vimrc ~/.vimrc
ln -s ~/editorconfig ~/.editorconfig
```
On first start install plugins:
```
:PlugInstall
```
