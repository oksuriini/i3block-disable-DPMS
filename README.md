# Disable DPMS shellscript

This is very simple, small, crude and extremely unreliable shellscript that disables DPMS on linux.

This is meant to be used with i3blocks to disable/enable DPMS with mouse click.

## Quick guide

Copy shellscript 'i3block-disable-dpms' to directory where you keep your i3blocks scripts.

Then create a block to your liking. As for example of my block:

```
[dpms-blocker]
full_text=test
command=~/.config/i3blocks/scripts/i3block-disable-dpms
interval=once
```

For command line, you should use your own scripts directory.
Interval should be left to once, as with integer script would be run every interval of that integer.

