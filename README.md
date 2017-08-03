## Settings
### Install neovim
```
brew install neovim/neovim/neovim
```

### Alias
```
vim ~/.bash_profile
alias vim='nvim'
```

### python3を使用しているプラグイン対応
```
brew update && brew upgrade
brew install pyenv
pyenv install 3.6.1
pyenv global 3.6.1
pip3 install --upgrade neovim
```

### Install dein.vim
```
cd ~/
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
mkdir ~/.cache/dein
sh ./installer.sh ~/.cache/dein
```
