## Requirements

```
brew install ghostty neovim git font-meslo-lg-nerd-font lazygit tree-sitter-cli curl fzf ripgrep fd
```

## Installation

### Clean

```
rm -rf ~/.config/nvim
rm -rf ~/.local/share/lazyvim-zero
```

### Install Lazy Vim

```
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
```

### Install Lazy Vim Zero

```
git clone https://github.com/lazaronixon/lazyvim-zero ~/.local/share/lazyvim-zero
cp -R ~/.local/share/lazyvim-zero/config/* ~/.config/
```

### Change the theme (optional)

```
cp ~/.local/share/lazyvim-zero/themes/[NAME]/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
cp ~/.local/share/lazyvim-zero/themes/[NAME]/ghostty.conf ~/.config/ghostty/theme.conf
```

## Guide

[Lazy Vim For Ambitious Developers](https://lazyvim-ambitious-devs.phillips.codes)
