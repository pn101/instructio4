# tmux

## Install
```
brew install tmux
```

## Create session
```
tmux new -s [type-name]
```

## Kill session
```
tmux kill-session -t [type-name]
```
or if you'd like to close current session
```
exit
```

> The default for initialising tmux commands inside tmux is `ctrl-b`.

## Split Pane (Vertical)
```
ctrl-b + "
```

## Split Pane (Horizontal)
```
ctrl-b + %
```

## Switch between Panes
```
ctrl-b + [arrow-key]
```

## List all tmux session
```
tmux ls
```

## Resize tmux Pane
```
ctrl-b + option + [arrow-key]
```

## New Window(Tab)
```
ctrl-b + c
```

## Switch between Windows
```
ctrl-b + [window-number]
```
