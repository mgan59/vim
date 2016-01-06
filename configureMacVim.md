# Configuring MacVIM and .vimrc

## Install Macvim

Install brew and get Xcode setup, then run

    brew install macvim --with-override-system-vim
    # put mac-vim icon into app folder
    brew linkapps --system

Which will give you ``mvim`` however there was no linking to ``vim``

Edited my ``.profile`` to now use

    alias vim='mvim '


## Prepare .vimrc and clone

### Checkout your .vimrc from github

[github.com/mgan59/vim](https://github.com/mgan59/vim)

Clone it first based on read me instructions then install bundle so it can overwite into the correct path ``.vim/bundle/vundle/``

Then copy/paste or symlink the .vimrc file into your local ``~/`` directory since vim needs it in order for vundle to be included on first run.  Then do ``:BundleInstall``

### Install Vundle

Need to install the [vundle](https://github.com/gmarik/vundle) project which is a package manager for vim.  Installation is essentially cloning the repo into place


