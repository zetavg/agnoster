# Fish Agnoster Theme

Fancy, colorful theme with support for Powerline fonts.

## Installation

You should use [Fisherman](https://github.com/fisherman/fisherman)

    fisher install zetavg/agnoster

Or [Fundle](https://github.com/tuvistavie/fundle)

    fundle plugin 'zetavg/agnoster'

## Themes

To choose theme run `agnoster <theme>`.

Available themes:

- `default`

  ![default theme](screenshots/default.png)

- `powerline`

  ![powerline theme](screenshots/powerline.png)

### Custom theme

You can create your own theme by setting these variables

```
# Segment endings
# AGNOSTER_SEGMENT_SEPARATOR[1] is separator of segment
# AGNOSTER_SEGMENT_SEPARATOR[2] is separator of subsegment
set -U AGNOSTER_SEGMENT_SEPARATOR '' \u2502 # unicode box drawings light vertical (│)

# Icons
set -U AGNOSTER_ICON_ERROR \u2717 # unicode ballot X (✗)
set -U AGNOSTER_ICON_ROOT \u26a1 # unicode high voltage sign (⚡)
set -U AGNOSTER_ICON_BGJOBS \u2699 # unicode gear (⚙)
set -U AGNOSTER_ICON_GIT_BRANCH \u2387 # unicode alternative key symbol (⎇)
set -U AGNOSTER_ICON_GIT_REF \u27a6 # unicode heavy black curved upwards and rightwards arrow (➦)
```

## Licence

Check [LICENSE](LICENSE)
