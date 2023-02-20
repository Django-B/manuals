# Tmux guide

## Tmux Commands
* **attach-session (attach)** - connect to an existing session. In the parameter you must pass option -t and session ID
* **detach-session (detach)** - disconnect all clients (or passed with option -t) from the session passed in option -s
* **has-session** - check if a session exists, pass the session identifier
* **kill-server** - stop all running sessions
* **kill-session** - terminate the session passed in the -t parameter
* **list-clients** - see the clients connected to the -t session
* **list-sessions (ls)** - display a list of all running sessions
* **new-session** - create a new session, you can pass the session name in the -s option and the start directory in the -c option
* **rename-session** - to rename the session, you need to pass the session ID and the new name

## Tmux HotKeys
* **Ctrl+b c** - create a new window
* **Ctrl+b w** - select a window from the list
* **Ctrl+b 0-9** - open a window by its number
* **Ctrl+b ,** - to rename the current window
* **Ctrl+b %** - split the current panel horizontally
* **Ctrl+b "** - split the current panel vertically
* **Ctrl+b <arrow>** - go to the panel on the side where the arrow points
* **Ctrl+b Ctrl+<arrow>** - resize the current panel
* **Ctrl+b o** - go to the next panel
* **Ctrl+b ;** - switch between the current and previous pane
* **Ctrl+b x** - close the current panel
* **Ctrl+b [** - enter copy mode
* **Ctrl+b ]** - paste from the internal clipboard tmux
* **Ctrl+b d** - disconnect from the current session
* **Ctrl+b :** - open the command line
