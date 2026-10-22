# dotfiles

Works on Ubuntu (bash) and macOS (zsh).

```
# git
ln -s ~/dotfiles/git/gitconfig ~/.gitconfig
gh auth login

# shell (adds to ~/.bashrc or ~/.zshrc, whichever your shell uses)
echo '. ~/dotfiles/bash/aliases' >> ~/.$(basename "$SHELL")rc
echo '. ~/dotfiles/bash/bashrc' >> ~/.$(basename "$SHELL")rc
exec "$SHELL"
```
