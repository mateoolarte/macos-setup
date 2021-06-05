# Config

Here you can find my OS config, prefs, apps and whatever I need to automate the workflow used on my pc. All of the configuration is based on macOS.

## TODO

-

## Shell setup

### Xcode command line utils
```sh
xcode-select --install
```
### [Homebrew](https://brew.sh) - The Missing Package Manager for macOS

```sh
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
With Homebrew comes `brew-cask` which will allow to install applications with the command line.

### ZSH - An alternative shell to Bash

```sh
brew install zsh
```
Add this to my `./zshrc`

```sh
export HOMEBREW_CASK_OPTS="--appdir=/Applications"
```

## Apps

- Authy Desktop
- Backup and Sync from Google
- Docker
- Firefox
- Flow
- Google Chrome
- ImageOptim
- Kindle
- Logi Options
- OmniDiskSweeper
- pgAdmin 4
- Postman
- Rectangle
- Slack
- Spotify
- The Unarchiver
- Visual Studio Code
- zoom.us

## Inspiration
[Mac-OS-Setup-Applications by David Dias
](https://github.com/thedaviddias/Mac-OS-Setup-Applications)
