# tmux-made-easy
Tmux configs and how-to's

## SET VI MODE
```
vi ~/.tmux.conf
set-window-option -g mode-keys vi

# inside the tmux session
Ctrl + B + :
source-file ~/.tmux.conf

# to enter COPY mode
Ctrl + B + [

# exit COPY mode at anytime
Ctrl + C

# forward, back
E, B

# entire line
V

# single character
space

# copy the desired selecttion
ENTER

# to end copy mode
press ESC twice
```

REF: \
TMUX - entering vi mode key binding \
https://stackoverflow.com/questions/67442428/tmux-entering-vi-mode-key-binding
