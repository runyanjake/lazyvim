# 💤 LazyVim
My LazyVim config, a sequel to runyanjake/nvim.  
Based off of `https://github.com/LazyVim/starter`.

## Install
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
1. 1. Back up existing nvim config
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
ln -sfn /path/to/original/README.md ~/.config/nvim/README.md
ln -sfn /path/to/original/lua ~/.config/nvim/lua
ln -sfn /path/to/original/init.lua ~/.config/nvim/init.lua
```
4. Start nvim, and let all the packages install. Done!


