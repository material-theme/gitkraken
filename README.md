## Installation [<img src="https://rawcdn.githack.com/material-theme/vsc-material-theme/790fc5d2872f10d5a903f449c90c1fa1502d7e53/logo.png" alt="Material Theme" width="90" height="90" align="right">](https://material-theme.site/)

```sh
npx degit material-theme/gitkraken ~/.gitkraken/themes --force
```
> ✅ MacOS only, Windows coming soon.


## Change default accent color

GitKraken theme files are just static jsonc files without any programmatic code. If you want to customize the default accent color from `teal` to another one, open the desired theme file from `~/.gitkraken/themes`, find the `"accent"` key and change the value as you wish.

Accent colors from Material Theme:

```sh
{
  "Acid Lime": "#C6FF00",
  "Blue": "#2979FF",
  "Breaking Bad": "#388E3C",
  "Bright Teal": "#64FFDA",
  "Cyan": "#00BCD4",
  "Graphite": "#616161",
  "Indigo": "#5C6BC0",
  "Lime": "#7CB342",
  "Orange": "#FF7042",
  "Pink": "#FF4081",
  "Purple": "#AB47BC",
  "Red": "#E57373",
  "Sky": "#84FFFF",
  "Tomato": "#F44336",
  "Teal": "#80CBC4",
  "Yellow": "#FFA000"
}
```

## Getting updates

Unfortunately, gitkraken doesn't provide a systematic way to get themes updates. The only thing you can do is manually checking for new releases and run the installation command again.

⚠️ Running the command again will override your local version of the themes. If you did some modification like changing the default accent color, this command will restore the default values. You'll lose your changes. ⚠️
