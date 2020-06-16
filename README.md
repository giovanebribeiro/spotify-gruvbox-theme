# spotify-gruvbox-theme (on DEV)

A gruvbox-like theme for Spotify.

## Installation

0. Install and configure spicetify properly (further instructions, see [here](https://github.com/khanhas/spicetify-cli)
1. Discover your config file location (just type `spicetify -c`)
2. Clone this repo inside the location of config file, under 'Themes' folder. We suggest change the repo
   folder to 'Gruvbox' (i.e. `git clone https://github.com/giovanebribeiro/spotify-gruvbox-theme
   /path_to_config_folder/Themes/Gruvbox`)
3. open the config file, and edit the following lines:

```ini
[Setting]

; other configurations

current_theme    = Gruvbox
color_scheme     = Dark ; or 'Light', you choose

; other configurations and sessions
```

1. Update the theme configurations (`spicetify update`)
2. Restart UI on Spotify (Ctrl + Shift + R)

## Screenshots


### Light mode

![Light Theme](/images/light.png)

### Dark mode

![Dark Theme](/images/dark.png)
