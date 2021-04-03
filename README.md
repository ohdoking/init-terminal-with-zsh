# init-terminal-with-zsh
init iterm2 with zsh

## Install homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Download iTerm2

```
brew cask install iterm2
```

## Install zsh
```
brew install zsh
```

## Install oh-my-zsh

Oh-My-Zsh is an open source, community-driven framework for managing your ZSH configuration

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Manage Plugins

Oh My Zsh comes bundled with plugins, which allow you to take advantage of functionality of many sorts to your shell just by enabling them.

check [this](https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins)

```
vi ~/.zshrc


# Which plugins would you like to load? (plugins can be found in ~/.oh-my-zsh/plugins/*)
# Custom plugins may be added to ~/.oh-my-zsh/custom/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
# Add wisely, as too many plugins slow down shell startup.
plugins=(
  git
  docker
)
```
## options

### Decorate Our iTerm2 With Material Design Colours

Open terminal and paste.
```
cd Downloads
curl -O https://raw.githubusercontent.com/MartinSeeler/iterm2-material-design/master/material-design-colors.itermcolors
```
2. Open iTerm2 that we already downloaded at the first section
3. Go to iTerm2 > Preferences > Profiles > Colors Tab
4. Click Color Presets… at the bottom right
5. Click Import…
6. Select the material-design-colors.itermcolors file
7. Select the material-design-colors from Load Presets…

### Apply Syntax Hightlight

```
brew install zsh-syntax-highlighting
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

## reference

- https://medium.com/ayuth/iterm2-zsh-oh-my-zsh-the-most-power-full-of-terminal-on-macos-bdb2823fb04c
- https://medium.com/harrythegreat/oh-my-zsh-iterm2%EB%A1%9C-%ED%84%B0%EB%AF%B8%EB%84%90%EC%9D%84-%EB%8D%94-%EA%B0%95%EB%A0%A5%ED%95%98%EA%B2%8C-a105f2c01bec

