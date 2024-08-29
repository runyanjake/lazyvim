# 💤 LazyVim
My LazyVim config, a sequel to runyanjake/nvim.  
Based off of `https://github.com/LazyVim/starter`.

## Installation

### Server
If cloning repo directly to `~/.config/nvim`:
1. Back up existing nvim config
```
mv ~/.config/nvim ~/.config/nvim_BAK
```
2. Clone this repo into a new nvim config folder.
```
gh repo clone runyanjake/lazyvim  ~/.config/nvim
```
3. Start nvim, and let all the packages install. Done!

If cloning repo to a seperate location:
1. Back up existing nvim config
```
mv ~/.config/nvim ~/.config/nvim_BAK
```
2. Clone this repo to wherever you're gonna keep it.
```
gh repo clone runyanjake/lazyvim  ~/repositories/lazyvim
```
3. Link all nvim related items to the nvim config folder.
```
ln -sfn /path/to/original/stylua.toml ~/.config/nvim/stylua.toml
ln -sfn /path/to/original/lua ~/.config/nvim/lua
ln -sfn /path/to/original/init.lua ~/.config/nvim/init.lua
```
4. Start nvim, and let all the packages install. Done!

### Client
**This example is installing Alacritty on MacOS**
1. For MacOS you can download a release from `https://github.com/alacritty/alacritty/releases` or get it using Homebrew
```
brew install --cask alacritty
```
2. Install a nerd font. This is just some one suggested online.
```
brew install font-meslo-lg-nerd-font
```
3. Create an Alacritty config:
```
mkdir -p ~/.config/alacritty
touch ~/.config/alacritty/alacritty.toml
```
and into that config add
```
[env]
TERM = "xterm-256color"

[window]
padding.x = 10
padding.y = 10

opacity = 0.7
blur = true

option_as_alt = "Both"

[font]
normal.family = "MesloLGS Nerd Font Mono"

size = 14
```


## Plugins/Addons

### Mason (Language Servers)
Enter Mason UI view from nvim: `:Mason`. Enter `g?` to toggle help page if you've forgotten the hotkeys. 
Some ideas of what to install:
- `java-language-server`
- `python-lsp-server`

## Shortcut Reference


