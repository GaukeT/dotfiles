# dotfiles

Manage the with https://www.chezmoi.io/

# Homebrew

apply according managed brewfile
```zsh
brew bundle cleanup --global
```

update brewfile to current state
```zsh
brew bundle dump --describe --force --global
chezmoi add ~/.homebrew/Brewfile
```

NOTE: the `--global` flag makes brew use the global Brewfile located at `~/.homebrew/Brewfile`.
