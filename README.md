# My Dev Environment Files 🚀
brew install iterm2 # Install iterm2

brew install zsh    # Install z Shell

# Intall Oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Auto Suggestions
brew install zsh-autosuggestions

#Syntax highlighting
brew install zsh-syntax-highlighting

# FzF
brew install fzf

# tf
brew install thefuck

# z
brew install zoxide

# Fonts for powerlevel10K
brew install powerlevel10k

omz update

# Oh-my-zsh theme
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k


