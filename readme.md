Steps:
1. Save com.bill.jupyter.plist to ~/Library/LaunchAgents
2. Edit the file and replace USERNAME with your username
3. In a terminal in the ~/Library/LaunchAgents directory run
launchctl load com.bill.jupyter.plist

And that should do it, it is setup as Login launch item