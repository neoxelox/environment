# ~/.tmux.conf

```conf
set-option -g prefix ^Space
set-option -g history-limit 99999
set -g status-bg green
set -g status-fg black
setw -g monitor-activity on
set -g visual-activity on
setw -g automatic-rename
bind . split-window -h
bind - split-window -v
set -g mouse on
set -s set-clipboard on
set -s set-clipboard external
set -s set-clipboard off
```
