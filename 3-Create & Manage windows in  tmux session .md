# Create & Manage windows in tmux sessions

## Create a new Session with window name

* start a new session with the name mysession and window mywindow

```
tmux new -s mysession -n mywindow
```

* Create a new window in a tmux session

```
press 'ctrl+b' then press 'c'

ctrl+b  c
```

## Switch/select window in a tmux session

* Goto Previous window in a tmux session

```
press 'ctrl+b' then press 'p'

ctrl+b p
```
* Goto Next window in a tmux session

```
press 'ctrl+b' then press 'n'

ctrl+b n
```

* Switch/select window by number

```
press 'ctrl+b' then press window number 
ctrl+b [ 0...9 ]
```

## Manage windows in a tmux session

* Rename current window in a tmux session

```
press 'ctrl+b' then press ','

ctrl+b ,
```

* Close current window in a tmux session

```
press 'ctrl+b' then press '&'

ctrl+b &
```

# References

* [tmuxcheatsheet](https://tmuxcheatsheet.com/)