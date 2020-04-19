```
███████╗██████╗ ██╗         ██╗      ██████╗  ██████╗ ████████╗███████╗██╗██╗     ███████╗███████╗
██╔════╝██╔══██╗██║         ╚██╗     ██╔══██╗██╔═══██╗╚══██╔══╝██╔════╝██║██║     ██╔════╝██╔════╝
█████╗  ██████╔╝██║    █████╗╚██╗    ██║  ██║██║   ██║   ██║   █████╗  ██║██║     █████╗  ███████╗
██╔══╝  ██╔══██╗██║    ╚════╝██╔╝    ██║  ██║██║   ██║   ██║   ██╔══╝  ██║██║     ██╔══╝  ╚════██║
███████╗██████╔╝██║         ██╔╝     ██████╔╝╚██████╔╝   ██║   ██║     ██║███████╗███████╗███████║
╚══════╝╚═════╝ ╚═╝         ╚═╝      ╚═════╝  ╚═════╝    ╚═╝   ╚═╝     ╚═╝╚══════╝╚══════╝╚══════╝
```

## Managing :nut_and_bolt:
I manage my dotfiles with [GNU Stow](http://www.gnu.org/software/stow/), a free, portable, lightweight symlink farm manager. This allows me to keep a versioned directory of all my config files that are virtually linked into place via a single command. Also, it makes sharing these files among many users (root) and computers super simple. It does not clutter your home directory with version control files.

## Installing :construction:
Stow is available for all linux and most other unix like distributions via your package manager.

- `sudo pacman -S stow`
- `sudo apt-get install stow`
- `brew install stow`

or clone it [from source](https://savannah.gnu.org/git/?group=stow) and [build it](http://git.savannah.gnu.org/cgit/stow.git/tree/INSTALL) yourself.

## Usage :mag:
1. Clone this repo whereever you want and `cd` to it.
2. Select a directory of your interest and simply stow it. 

(e.g.) In order to have my fontconfig, run this: `stow -v -t $HOME font`

## Support 💰
Consider :star: this repo.

You also can donate :credit_card: to [me](https://zarinp.al/@simplyebi) in Rials.

## License :page_facing_up:
All are licensed under GPLv3.
