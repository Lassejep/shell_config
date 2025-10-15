# Shell configuration

## Dependencies
- [zsh](https://www.zsh.org/)
- [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
- [stow](https://www.gnu.org/software/stow/)
- [git](https://git-scm.com/)

## Installation
### Clone and link the configuration files
```bash
mkdir -p ~/git
git clone https://github.com/lassejep/shell_config.git ~/git/
cd ~/git/shell_config
stow --dotfiles -t ~/ .
```

### Change your default shell
```bash
chsh -s $(which zsh)
```
