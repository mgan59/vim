vim
===

To set up on a new machine:

1. `rm -rf ~/.vim` (backup first if necessary)
2. `mkdir ~/.vim && cd ~/.vim`
2. `git init`
3. `git remote add origin git@github.com:mcraft59/vim.git`
4. `git pull origin master`
5. Clone the vundle project (submodule) `git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle`
6. SymLink `ln -s ~/.vim/.vimrc ~/.vimrc`
6. Or copy .vimrc `cp ~/.vim/.vimrc ../.vimrc`
7. Launch vim and run `:BundleInstall`
8. Install macvim
9. So you can use rebase `git config --global core.editor "mvim -f"`

View the [macosx instructions](configureMacVim.md) about installing MacVim using brew

Compile YCM using instructions @ https://github.com/Valloric/YouCompleteMe
