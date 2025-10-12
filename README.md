
<img width="1512" height="982" alt="screenshot" src="https://github.com/user-attachments/assets/64912cba-45e8-44f8-b704-db4c7a283d26" />

## Requirements

```
brew install alacritty neovim font-meslo-lg-nerd-font lazygit tree-sitter-cli fzf ripgrep fd
```

## Installation

### Clean Up

```
rm -rf ~/.config/nvim
rm -rf ~/.config/alacritty
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
cp ~/.local/share/lazyvim-zero/themes/gruvbox/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
cp ~/.local/share/lazyvim-zero/themes/gruvbox/alacritty.toml ~/.config/alacritty/theme.toml
```

## Run

Open Alacritty, and type nvim <kbd>Enter</kbd>.

## Guide

[Lazy Vim For Ambitious Developers](https://lazyvim-ambitious-devs.phillips.codes)
