# ~/.gitconfig

```ini
[user]
  name = Alex
  email = me@arn.sh

[color]
  ui = true

[init]
  defaultBranch = main

[color "branch"]
  current = yellow reverse
  local = yellow
  remote = green

[color "diff"]
  meta = yellow bold
  frag = magenta bold
  old = red bold
  new = green bold

[alias]
  amend = commit --amend
  ammend = commit --amend
  pamrebase= !HASH=`git log --pretty=oneline | head -n 50 | fzf` && git rebase -i `echo ${HASH} | awk '{ print $1 }'`^

[grep]
  linenumber = true

[format]
  pretty = format:%C(blue)%ad%Creset %C(yellow)%h%C(green)%d%Creset %C(blue)%s %C(magenta) [%an]%Creset

[merge]
  summary = true
  verbosity = 1

[apply]
  whitespace = nowarn

[branch]
  autosetuprebase = always

[push]
  default = tracking
  autoSetupRemote = true

[pull]
  ff = only

[core]
  autocrlf = false
  editor = /opt/homebrew/bin/micro
  excludesfile = $HOME/.gitignore_global

[advice]
  statusHints = false

[diff]
  mnemonicprefix = true

[rerere]
  enabled = true
```
