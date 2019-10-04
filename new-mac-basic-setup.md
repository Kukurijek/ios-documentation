# new-mac-basic-setup
Setup for the new mac - must have
<br>

* [Homebrew](https://brew.sh) - Package manager for macOS
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
<br>

* [Oh My ZSH](https://ohmyz.sh) - Framework for Z shell
```bash
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
<br>


* [iTerm2](https://www.iterm2.com) - Terminal emulator
```bash
brew cask install iterm2
```
<br>


* [Git](https://git-scm.com) - VERSION-CONTROL SYSTEM
```bash
brew install git
```
<br>


* [SSH](https://de.wikipedia.org/wiki/Secure_Shell) - Create ssh key pair
```bash
ssh-keygen -t rsa -b 4096 (-C youremail@lalala.com)
```
or even better
```bash
ssh-keygen -t ecdsa (-C youremail@lalala.com)
```
or the best method
```bash
ssh-keygen -t ed25519 (-C youremail@lalala.com)
```

PLEASE do not use DSA!!!
<br>



* [Google Chrome](https://www.google.com/chrome/) - Realy convenient browser for development
```bash
brew cask install google-chrome
```
<br>


* [Visual Studio Code](https://code.visualstudio.com) - Best IDE for script languages
```bash
brew cask install visual-studio-code
```
<br>


* [Sublime Text](https://www.sublimetext.com) - Nice editor
```bash
brew cask install sublime-text
```
<br>



* [Node](https://nodejs.org) - For JS on backend
```bash
brew install node
```
or even better
```bash
brew install nvm
```
<br>

* [Python](https://www.python.org) - Python for all kind of scripts
```bash
brew install python
```
or even better
```bash
brew install pyenv
```
<br>



* [SapMachine - OpenJDK](https://sap.github.io/SapMachine/) - Required for Java (latest JDK)
```bash
brew cask install sapmachine-jdk
```
<br>

* [Eclipse](https://sap.github.io/SapMachine/) - IDE for Java
```bash
brew cask install eclipse-java
```
<br>

* [KeepassXC](https://keepassxc.org) - Sofware for keeping passwords safe
```bash
brew cask install keepassxc
```
<br>




* [Xcode](https://developer.apple.com/xcode/) - IDE for Swift


