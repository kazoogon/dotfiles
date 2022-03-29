# 🏋️‍♂️ Dotfiles
## Usage
```
// install oh-my-zsh
$ git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh

// create synbolic link
$ cd ~
$ cd dotfiles
$ sh link.sh
```

## node version management
- [nodenv](https://github.com/nodenv/nodenv)  
Easy to change node version for each directory  
[good ref](https://r17n.page/2019/08/10/nodejs-change-version-directory/)

need to add in ~/.bashrc (If you you zsh, ~/.zshrc)
```
export PATH="$HOME/.nodenv/bin:$PATH"
eval "$(nodenv init -)"
```
