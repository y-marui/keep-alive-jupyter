# Keep Alive Jupyter
Forked from [wjladams/com.bill.jupyter.plist](https://gist.github.com/wjladams/71c03cf11f299694dce8e9eebed5ef4b)

## Install to LaunchAgents (Run at login)
```zsh
ln -s $(pwd)/com.bill.jupyter.plist ~/Library/LaunchAgents/com.bill.jupyter.plist
launchctl load ~/Library/LaunchAgents/com.bill.jupyter.plist
```

if you modify the plist, use `cp` instead of `ln -s`.

## Install from LaunchAgents
```zsh
launchctl unload ~/Library/LaunchAgents/com.bill.jupyter.plist
```
