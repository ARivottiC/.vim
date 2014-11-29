# .vim

My VimL setup

Installation

```sh
# clone
git clone https://github.com/ARivottiC/.vim.git ~/.vim
cd ~/.vim

# init submodules
git submodule update --init --recursive

# use rivotti.vim/.vimrc
ln -s ~/.vim/bundle/rivotti.vim/.vimrc ~/.

# install YouCompleteMe
cd bundle/YouCompleteMe
./install.sh

# install command-t
cd ~/.vim/bundle/command-t/ruby/command-t
ruby extconf.rb
make

# install livedown
sudo npm install -g livedown
```
