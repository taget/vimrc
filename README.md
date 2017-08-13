vimrc
=====

my vimrc config

Installation
============
    git clone https://github.com/pyKun/vimrc ~/.vim
    cp ~/.vim/.vimrc ~/
    cd ~/.vim/
    git submodule init
    git submodule update
    sudo apt-get install exuberant-ctags

YCM
===

YCM requires vim vesion to higher than 7.4.1578+. (ubuntu 16.04)

    sudo apt-get install python-dev python3-dev
    sudo apt-get install build-essential cmake
    cd ~/.vim/bundle/YouCompleteMe
    ./install.py --all
