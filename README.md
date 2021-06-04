# .cfg

This software is provided as is and provides no warranty, use at your own risk.

Always read the source code of anything you're installing.

Pull this repository
```
git clone https://github.com/DanielTate/.cfg.git
alias config '/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
config restore --staged .dot
config restore --staged .config
config config --local status.showUntrackedFiles no
```

Install dependancies
```
.dot/.scripts/./install
```

@TODO
Add other steps to get everythign running correctly.
