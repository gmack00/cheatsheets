
# Emacs Cheatsheet

## Files and Buffers
| Action          | Key Binding |
| ----------------| ---------- |
| Open file | C-x C-f |
| Save file | C-x C-s |
| Save as | C-x C-w |
| Save all open buffers | C-x s |
| Move to buffer (enter name) | C-x b |
| List buffers | C-x C-b |
| Export to HTML | C-c C-e h h |


## Cursor

### Movement
| Scope | Action          | Key Binding |
| ------| ----------------| ---------- |
| Character | Forward | C-f |
| Character | Backward | C-b |
| Character | Up | C-p |
| Character | Down | C-n |
| Character | Delete forward | C-d
| Character | Delete backward | DEL |
| Word | Forward | M-f |
| Word | Backward | M-b |
| Word | Delete forward | M-d |
| Line | Up | C-p |
| Line | Down | C-n |
| Line | Delete | C-k |
| Line | Move to end | C-e |
| Line | Move to start | C-a |
| Sentence | Forward | M-e |
| Sentence | Backward | M-a |
| Sentence | Delete | M-k |

### Operations
| Action          | Key Binding |
| ----------------| ---------- |
| Undo/Redo | C-/ |

## Searching and Replacing
| Action          | Key Binding |
| ----------------| ---------- |
| Search forward | C-s |
| Search backward | C-r |
| Regex search forward | C-M-s |
| Regex search backward | C-M-r |
| Replace string from cursor to end of buffer | M-x [replace string] RET |


## Scrolling and Windows

| Action          | Key Binding |
| ----------------| ---------- |
| Scroll Down | C-v |
| Scroll Up | M-v |
| Reduce Windows to one | C-x 1 |
| Split window vertically | C-x 2 |
| Split window horizontally | C-x 3 |


## Cutting and Pasting
| Action          | Key Binding |
| ----------------| ---------- |
| Start Highlight | C-SPACEBAR |
| Cut             | C-w        |
| Copy            | M-w        |
| Yank/Paste      | C-y        |


Cut

Delete line C-k
Move line up
Move line down


## Command Management
| Action          | Key Binding |
| ----------------| ---------- |
| Escape | ESC ESC |
| Repeat # of times | C-u # [command] |
| Stop command in progress | C-g |


Credit to [David Cohen/Bob Rogers](http://www.rgrjr.com/emacs/emacs_cheat.html)
