List keys
---

* `list-keys -t vi-copy`

Sessions
---

* `tmux list-sessions`
* `tmux attach [session_name]`
* `tmux new` - Create a new session

Panes
---

* `:setw synchronize-panes on|off` - Send commands to all panes
* `C-b {` 
* `C-b }` - Shift panes left or right
* `C-b z` - Zoom/ unzoom pane
* `C-b x`- Close panel

Windows
---

* `C-b (`
* `C-b )` - Cycle through windows
* `C-b c` - Create new window
* `C-b 0..9` - Switch to windows by number
* `C-b p` - Switch to prev window
* `C-b m` - Switch to next window
* `C-b l` - Switch to previously active window
* `C-b &` - Close window
* `C-b d` - Detach Tmux
