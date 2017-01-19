# tmux Cheatsheet
Once `tmux` has been started, control are initiated with the `C-b` sequence  

Credit to [MohamedAlaa](https://gist.github.com/MohamedAlaa/2961058)

## Operations
| Action          | Key Binding |
| ----------------| ---------- |
| New session | tmux |
| New session with name | tmux new -s [name] |
| Attach to existing session | tmux a |
| Attach to named session | tmux a -t [name]|
| List sessions | tmux ls |
| Kill session | tmux kill-session -t [name] |
| Detach from session | C-b d |


## Windows
All these actions begin with `C-b`

| Action          | Key Binding |
| ----------------| ---------- |
| Create new window | c |
| List windows | w |
| Next window | n |
| Previous window | p |
| Find window | f |
| Name window | , |
| Kill window | & |

## Panes
| Action          | Key Binding |
| ----------------| ---------- |
| Vertical split | % |
| Horizontal split | " |
| Kill pane | x |

## Misc
| Action          | Key Binding |
| ----------------| ---------- |
| Scroll/copy mode | [ |
|
