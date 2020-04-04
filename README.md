# Roberto's Vim configuration

### Quick install
* install fuzzy finder    
`brew install fzf` (for OSX)    
* remove `.vimrc` from home directory
* create link from vimrc in this folder to a .vimrc in home directory   
`ln ~/.vim/vimrc ~/.vimrc`   
* clone vundle into this git repo    
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`   
* open vim and run `:PluginInstall`   
* Follow the YCM installation instructions found here https://github.com/ycm-core/YouCompleteMe#installation   
* If you're on OSX ensure you are using mvim. You can look at how we do this in in the config repo alias.sh file https://github.com/robertoodogherty/config   
