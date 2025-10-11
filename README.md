## Install requirements

```
brew install neovim git font-meslo-lg-nerd-font lazygit tree-sitter-cli curl fzf ripgrep fd
```

## Install LazyVimZero

### Remove previous configuration files

```
rm -rf ~/.config/nvim
```

### Install LazyVim

```
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
```

### Overwrite configuration

```
git clone https://github.com/lazaronixon/lazyvim-zero ~/lazyvim-zero
cp -R ~/lazyvim-zero/config/nvim/* ~/.config/nvim/
```

### Set font to MesloLGS Nerd Font

Go to Terminal -> Settings -> Font -> Change...

### Change the theme (optional)

```
cp ~/lazyvim-zero/themes/[NAME]/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
```
