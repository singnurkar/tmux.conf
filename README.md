List keys
---

* `list-keys -t vi-copy`

Sessions
---

* `tmux list-sessions`
* `tmux attach [session_name]`
* `tmux new -s [session_name]` - Create a new session
* `tmux ls` - list all sessions
* `C-b $` - list all sessions
* `:new` - New session
* `C-b s` - List sessions
* `C-b $` - (Re)name session

Panes
---
* `:setw synchronize-panes on|off` - Send commands to all panes
* `C-<Space>` - Auto rearrange panes
* `C-b {` 
* `C-b }` - Shift panes left or right
* `C-b z` - Zoom/ unzoom pane
* `C-b x`- Close panel
* `:break-pane` - Break pane out into window

Windows
---

* `C-b (`
* `C-b )` - Cycle through windows
* `C-b c` - Create new window
* `C-b 0..9` - Switch to windows by number
* `C-b p` - Switch to prev window
* `C-b m` - Switch to next window
* `C-b l` - Switch to previously active window
* `C-b w` - List all windows
* `C-b &` - Close window
* `C-b d` - Detach Tmux
