# zhuralol's EXPerience Plugin

Yet another Pwnagotchi experience plugin. Get experience from Associations, Deauths and Handshakes.
Try to level it up!

Based on Gaelic Thunder's work - https://github.com/GaelicThunder/Experience-Plugin-Pwnagotchi
Updated for the jayofelony's pwnagotchi image - https://github.com/jayofelony/pwnagotchi/

![EXP Plugin](zh_exp.jpg)


## Setup
1. Copy over `exp.py` into your custom plugins directory (usually `/usr/local/share/pwnagotchi/custom-plugins/`)
2. Please check that you do not have any similar plugins already! Like `xp.py`. That might break things.
3. In your `config.toml` file (use the `config` command for that), add:
```toml
   [main.plugins.exp]
   enabled = true
   lvl_x_coord = 156
   lvl_y_coord = 72
   exp_x_coord = 196
   exp_y_coord = 72
   bar_symbols_count = 12
```
3. Restart your device to see your new plugin! You can use the `pwnkill` command for that.


## Things to do
  
- [ ] Remove remnants of old Save System.
- [ ] Remake EXP calculation for handshakes captured before installation.
- [ ] Testing, lots of testing.
- [ ] Refactor the old code.

## License
 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)