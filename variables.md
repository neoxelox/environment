```sh
# ZSH
export ZSH="$HOME/.oh-my-zsh"

# GO
export PATH="$PATH:/usr/local/go/bin"
export GOPATH="$HOME/go"

# PYTHON
export PATH="$PATH:$HOME/.local/bin"

# BINS
export PATH="$PATH:/snap/bin"

# ALIASES
alias cat="batcat"
alias curl="curlie"
alias ls="ls --color"
alias python="python3"
alias pip="pip3"
alias folder="nautilus . &"
alias gtree="git log --graph --abbrev-commit --decorate --date=relative --format=format:'\''%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)'\'' --all"

# THEME
ZSH_THEME="robbyrussell"

# PLUGINS
plugins=(git fzf)
```
