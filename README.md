# 💤 LazyVim
My LazyVim config, a sequel to runyanjake/nvim.  
Based off of `https://github.com/LazyVim/starter`.

## Installation

### Server
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

#### MacOS
1. Download a release from `https://github.com/alacritty/alacritty/releases` or get it using Homebrew
```
brew install --cask alacritty
```
2. Install a nerd font. This is just some one suggested online.
```
brew install font-meslo-lg-nerd-font
```
3. Create an Alacritty config folder and link the alacritty config in this repo into there.
```
mkdir -p ~/.config/alacritty
ln -sfn /Users/runyanjake/Desktop/repositories/lazyvim/alacritty-macos.toml ~/.config/alacritty/alacritty.toml
```

#### Ubuntu
1. Install Alacritty through a third-party PPA.
```
sudo add-apt-repository ppa:aslatter/ppa
sudo apt update
sudo apt install alacritty
```
2. Install a nerd font (I am using "MesloLG Nerd Font" from  `https://www.nerdfonts.com/font-downloads`)
```
unzip Meslo.zip -d Meslo
mkdir ~/.local/share/fonts
cp Meslo/*.ttf ~/.local/share/fonts
fc-cache -fv
rm -r Meslo Meslo.zip
```
3. Create an Alacritty config folder and link the alacritty config in this repo into there.
```
mkdir -p ~/.config/alacritty
ln -sfn /home/jrunyan/repos/lazyvim/alacritty-ubuntu.toml ~/.config/alacritty/alacritty.toml
```

## Plugins/Addons

### Mason (Language Servers)
Enter Mason UI view from nvim: `:Mason`. Enter `g?` to toggle help page if you've forgotten the hotkeys. 
Some ideas of what to install:
- `java-language-server`
- `python-lsp-server`

## Shortcut Reference
`<LEADER>` key is space by default. I don't see a need to change it for me.

