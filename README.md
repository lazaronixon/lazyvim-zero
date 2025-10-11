## Requirements

```
brew install neovim git font-meslo-lg-nerd-font lazygit tree-sitter-cli curl fzf ripgrep fd
```

## Installation

### Install Lazy Vim

```
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
```

### Install Lazy Vim Zero

```
git clone https://github.com/lazaronixon/lazyvim-zero ~/.local/share/lazyvim-zero
cp -R ~/.local/share/lazyvim-zero/config/nvim/* ~/.config/nvim/
```

### Set font to MesloLGS Nerd Font

```
Go to Terminal -> Settings -> Font -> Change...
```

### Change the theme (optional)

```
cp ~/.local/share/lazyvim-zero/themes/[NAME]/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
```

## Guide

[Lazy Vim For Ambitious Developers](https://lazyvim-ambitious-devs.phillips.codes)
