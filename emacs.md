
# Emacs Cheatsheet
Common emacs actions

*Table of Contents*
- [Files and Buffers](#files_buffers)
- [Cursor](#cursor)
  - [Movement](#cursor_movment)
  - [Operations](#cursor_operations)
- [Searching and Replacing](#searching)
- [Scrolling and Windows](#scrolling)
- [Cutting and Pasting](#cutting)
- [Command Management](#command_management)
- [Org Mode](#org-mode)


Credit to [David Cohen/Bob Rogers](http://www.rgrjr.com/emacs/emacs_cheat.html)

## <a name="files_buffers">Files and Buffers</a>
| Action          | Key Binding |
| ----------------| ---------- |
| Open file | C-x C-f |
| Save file | C-x C-s |
| Save as | C-x C-w |
| Save all open buffers | C-x s |
| Move to buffer (enter name) | C-x b |
| List buffers | C-x C-b |
| Export to HTML | C-c C-e h h |


## <a name="cursor">Cursor</a>

### <a name="cursor_movment">Movement</a>
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

### <a name="cursor_operations>Operations</a>
| Action          | Key Binding |
| ----------------| ---------- |
| Undo/Redo | C-/ |

## <a name="searching">Searching and Replacing</a>
| Action          | Key Binding |
| ----------------| ---------- |
| Search forward | C-s |
| Search backward | C-r |
| Regex search forward | C-M-s |
| Regex search backward | C-M-r |
| Replace string from cursor to end of buffer | M-x [replace string] RET |


## <a name="scrolling">Scrolling and Windows</a>

| Action          | Key Binding |
| ----------------| ---------- |
| Scroll Down | C-v |
| Scroll Up | M-v |
| Reduce Windows to one | C-x 1 |
| Split window vertically | C-x 2 |
| Split window horizontally | C-x 3 |


## <a name="cutting">Cutting and Pasting</a>
| Action          | Key Binding |
| ----------------| ---------- |
| Start Highlight | C-SPACEBAR |
| Cut             | C-w        |
| Copy            | M-w        |
| Yank/Paste      | C-y        |

## Command Management
| Action          | Key Binding |
| ----------------| ---------- |
| Escape | ESC ESC |
| Repeat # of times | C-u # [command] |
| Stop command in progress | C-g |

# <a name="org-mode">Org Mode Cheatsheet</a>
