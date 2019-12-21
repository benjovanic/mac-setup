# Homebrew

## Install Homebrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Install apps

```
brew install nvm maven
brew cask install iterm2
```

# zsh setup

## Install zsh

```
brew install zsh
```

## Install oh my zsh

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Install theme for iTerm2

```
cd Downloads
curl -O https://raw.githubusercontent.com/MartinSeeler/iterm2-material-design/master/material-design-colors.itermcolors
```

> Go to iTerm2 > Preferences > Profiles > Colors Tab

# GPG setup

```
brew install gnupg
cd
mkdir ~/.gnupg
cd ~/.gnupg
mv gpg-agent.conf gpg-agent.conf.bak
wget https://raw.githubusercontent.com/drduh/config/master/gpg-agent.conf
```
