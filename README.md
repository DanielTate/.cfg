# .cfg

This software is provided as is and provides no warranty, use at your own risk.

Always read the source code of anything you're installing.

To install run

```
git clone https://github.com/DanielTate/.cfg.git
alias config '/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
config restore --staged .dot
config restore --staged .config
config config --local status.showUntrackedFiles no
```
