screen_configs
========

My screen_configs directory. Contains a collections of screen rc files
for various tasks. It's intended to be used with an ```scr``` method
from your .zshrc file that looks like ...

```bash
# Special screens
# $1 - screen config file name
scr() { screen -c ~/screen_configs/$1 }
```

and called with ...

```scr rails```

## Installation
From your home directory ...

```git clone https://github.com/slabounty/screen_configs.git```
