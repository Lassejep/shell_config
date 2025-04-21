# Shell configuration

## Dependencies
- [zsh](https://www.zsh.org/)
- [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
- [stow](https://www.gnu.org/software/stow/)

## Installation
### Clone and link the configuration files
```bash
git clone https://github.com/lassejep/shell_config.git ~/git
cd ~/git/shell_config
stow --dotfiles -t ~/ .
```

### Change your default shell
```bash
chsh -s $(which zsh)
```
