# Shell Preferences

My preferred shell setup (zsh). Includes highlights, and a whole bunch of aliases to make your life better :) 

## Setup
```sh
# clone this repo to ~/code
git clone git@github.com:emattson/bash-profile.git

# Install OhMyZShell
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install spaceship theme
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme" 

# replace ~/.zshrc
mv ~/.zshrc ~/.zshrc.old
cp .zshrc ~/.zshrc

# try it out 
source ~/.zshrc
```
