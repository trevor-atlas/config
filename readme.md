# My XDG compliant dotfiles

## Install

### oh-my-zsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### dotfiles
```
git clone https://github.com/trevor-atlas/config ~/.config/atlas &&\
echo "source $HOME/.config/atlas/index" >> .zshrc &&\
source "$HOME/.zshrc" &&\
install_dotfiles_once
```

this will:
1. install oh-my-zsh
2. clone this repository into ~/.config/atlas
3. source the index file that exports all of the aliases, functions and environment variables
4. run the install script that sets up Macos preferences, installs homebrew and my preffered apps.
