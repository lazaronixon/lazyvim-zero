# Install requirements

```
brew install neovim git font-meslo-lg-nerd-font lazygit tree-sitter-cli curl fzf ripgrep fd
```

# Install LazyVimZero

```
# Install LazyVim
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git

# Overwrite configuration
cp -R ./config/nvim/* ~/.config/nvim/
```
