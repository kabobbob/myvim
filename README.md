Installation:

    git clone https://github.com/kabobbob/myvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, create backup dir, and fetch submodules:

    cd ~/.vim
    mkdir backup
    git submodule init
    git submodule update
