# dotfiles
This project is designed to be run using GNU Stow. You can also manage the symlinks yourself or
copy the files manually.

- Install Stow (`brew install stow`)
- Clone this project into your home directory
- `stow git vim intellij` (or pick a subset to apply)

### Global gitignore
Make sure you use an absolute path for the global gitignore configuration.

```
git config --global core.excludesfile ~/.gitignore_global
```
