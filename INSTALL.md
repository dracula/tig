### [Tig](https://jonas.github.io/tig)

### Introduction

According to the [tigrc documentation](https://jonas.github.io/tig/doc/tigrc.5.html#_color_command) valid colors are limited to white, black, green, magenta, blue, cyan, yellow, red, default. Default refers to the default terminal colors. Due to the limitation on available colors, it appears the best option is to theme your terminal, then adjust the tigrc 

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/tig.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/tig/archive/master.zip) option and unzip them.

#### Activating theme

1) Install the [Dracula theme](https://draculatheme.com/) on your terminal.

* [Alacritty](https://draculatheme.com/alacritty)
* [Fluent Terminal](https://draculatheme.com/fluent-terminal)
* [Foot](https://draculatheme.com/foot-terminal)
* [Gnome Terminal](https://draculatheme.com/gnome-terminal)
* [Hyper](https://draculatheme.com/hyper)
* [iTerm](https://draculatheme.com/iterm)
* [Kitty](https://draculatheme.com/kitty)
* [Terminal](https://draculatheme.com/terminal)
* [Terminator](https://draculatheme.com/terminator)
* [Termite](https://draculatheme.com/termite)
* [Termux](https://draculatheme.com/termux)
* [Windows Terminal](https://draculatheme.com/windows-terminal)
* [Xfce4 Terminal](https://draculatheme.com/xfce4-terminal)

2) Determine the config directory for the tigrc file. The default location is `~/.tigrc`. In some environments, a user’s configuration will be stored in the alternate location `$XDG_CONFIG_HOME/tig/config`

3) Copy the contents of this repositories config file into your tig config file.