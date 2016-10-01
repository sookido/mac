# mac

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew update
brew upgrade

brew tap caskroom/cask || true
brew tap homebrew/binary || true
brew tap caskroom/versions || true

brew install brew-cask
brew install zsh
brew install git
brew install vim
brew install findutils
brew install smartmontools
brew install tmux

brew cask install iterm2 || true
brew cask install java || true
brew cask install google-chrome || true
brew cask install virtualbox || true
brew cask install google-japanese-ime || true
brew cask install vlc || true
brew install Caskroom/cask/android-studio
brew install Caskroom/cask/the-unarchiver
brew install Caskroom/cask/atom

brew cleanup
```
