# Homebrew

## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo "# Homebrew\nexport PATH=/opt/homebrew/bin:\$PATH" >> .zshrc
source ~/.zshrc
```

## Install maven

```
brew install maven
```

# Install nvm

```
brew update
brew install nvm
mkdir ~/.nvm

echo "export NVM_DIR=~/.nvm\nsource \$(brew --prefix nvm)/nvm.sh" >> .zshrc
source ~/.zshrc
```

# zsh setup

## Install zsh

```
brew install zsh
```

## Install oh my zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install theme for iTerm2

https://github.com/MartinSeeler/iterm2-material-design

# GPG setup

```
brew install gnupg
cd
mkdir ~/.gnupg
cd ~/.gnupg
mv gpg-agent.conf gpg-agent.conf.bak
wget https://raw.githubusercontent.com/drduh/config/master/gpg-agent.conf
```
