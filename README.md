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
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Note: Follow [this](https://earthly.dev/blog/homebrew-on-m1/) instructions for M1 Chip

With Homebrew comes `brew-cask` which will allow to install applications with the command line.

Copy content from `.zshrc` in this repo

Add this to my `./zshrc`

```sh
export HOMEBREW_CASK_OPTS="--appdir=/Applications"
```

## Apps

- Arc (Browser)
- Authy Desktop
- Google Drive
- Docker
- Figma
- Firefox
- Flow
- Google Chrome
- Google Drive
- ImageOptim
- Logi Options+
- OmniDiskSweeper
- Postman
- Raycast
- Slack
- Spotify
- The Unarchiver
- TunnelBear
- Visual Studio Code
- zoom.us

https://sourabhbajaj.com/mac-setup/

https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line

https://github.com/nvm-sh/nvm

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

https://github.com/tonsky/FiraCode/wiki/Installing

https://www.nerdfonts.com/font-downloads

https://ohmyz.sh/#install

https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md

https://spaceship-prompt.sh/getting-started/

## Inspiration

- [Mac-OS-Setup-Applications by David Dias](https://github.com/thedaviddias/Mac-OS-Setup-Applications)
- [macOS Ventura: Set up a Mac for Development by Lauro Silva](https://www.laurosilva.com/posts/set-up-a-mac-for-development)
