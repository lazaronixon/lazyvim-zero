![screenshot](https://github.com/user-attachments/assets/6a0a75bb-2e75-4b01-917c-07e40fbf6456)

## Requirements

```
brew install neovim lazygit tree-sitter-cli fzf ripgrep fd
brew install --cask ghostty font-jetbrains-mono-nerd-font
```

## Installation

### Clean Up

```
rm -rf ~/.config/nvim
rm -rf ~/.config/ghostty
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
cp -r ~/.local/share/lazyvim-zero/config/* ~/.config/
```

```
echo "vim.opt.relativenumber = false" >> ~/.config/nvim/lua/config/options.lua
```

### Change the theme (optional)

```
cp ~/.local/share/lazyvim-zero/themes/gruvbox/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
cp ~/.local/share/lazyvim-zero/themes/gruvbox/alacritty.toml ~/.config/alacritty/theme.toml
```

## Run

Open Ghostty, and type nvim <kbd>Enter</kbd>.

## Guide

[Lazy Vim For Ambitious Developers](https://lazyvim-ambitious-devs.phillips.codes)
