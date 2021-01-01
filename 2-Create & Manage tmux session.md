# Create & Manage tmux session 


## Create Sessions

* Start a new session

```
tmux
```

* Start a new session with the name mysession

```
tmux new -s session_name
```

## List tmux session

* Show all sessions

```
tmux ls 
```

* First press ctrl + b after that press s

```
ctrl + b s
```

## Attach to a session

* Attach to a session with the session name

```
tmux a -t session_name
```
* Attach to last session

```
tmux a
```

## Detach from a Session

* detach from a session

```
tmux detach  
 
   ( or )
   
press "ctrl + b" and then press "d"  

ctrl + b d
```

## Rename session

* Rename a particular session

```
press "ctrl + b" and then press "$"

ctrl + b $
```

## Kill Session

* kill / delete a session with sessionName

```
tmux kill-ses -t sessionName
         
         (or)
         
tmux kill-session -t sessionName
```

* kill / delete all sessions except the current session

```
tmux kill-session -a
```

* kill / delete all sessions except mysession

```
tmux kill-session -a -t mysession
```

## Shift between sessions

* Move to previous session

```
ctrl + b (
```
* Move to next session

```
ctrl + b )
```

## tmux help

* Show every session, window, pane, etc...

```
tmux info
```

* Show shortcuts

```
press "ctrl + b" and then press "?"

ctrl+b ?
```
# References

* [tmuxcheatsheet.com](https://tmuxcheatsheet.com/)