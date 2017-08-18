# My Powerline Stuffs

## Installation

```
pip install --user powerline-status
pip install --user powerline-gitstatus
```

Add to your .bashrc:
```
export PATH=/home/jawa/.local/bin:$PATH
powerline-daemon -q
POWERLINE_BASH_CONTINUATION=1
POWERLINE_BASH_SELECT=1
. /home/jawa/.local/lib/python2.7/site-packages/powerline/bindings/bash/powerline.sh
```

Deploy configuration in '/home/jawa/.config/powerline'

## Useful links

*  https://powerline.readthedocs.io
*  https://nerdfonts.com/
*  https://github.com/jaspernbrouwer/powerline-gitstatus
