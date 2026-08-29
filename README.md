<img width="1512" height="982" alt="Screenshot" src="https://github.com/user-attachments/assets/a6f8af7a-9f97-4b44-b9d4-d160f147f710" />

## Requirements

```
brew install --cask ghostty
brew install --cask font-jetbrains-mono-nerd-font
brew install neovim lazygit tree-sitter-cli fzf ripgrep fd
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
echo "vim.g.autoformat = false" >> ~/.config/nvim/lua/config/options.lua
```

### Change the theme (optional)

```
cp ~/.local/share/lazyvim-zero/themes/gruvbox/neovim.lua ~/.config/nvim/lua/plugins/theme.lua
cp ~/.local/share/lazyvim-zero/themes/gruvbox/ghostty.toml ~/.config/ghostty/theme.toml
```

## Run

Open Ghostty, and type nvim <kbd>Enter</kbd>.

## Guide

[Lazy Vim For Ambitious Developers](https://lazyvim-ambitious-devs.phillips.codes)
