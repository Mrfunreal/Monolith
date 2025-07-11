# Monolith

A sleek and simple theme for Spicetify.<br> 
Most everything is dark, with some colorful highlights, the color of shich you can modify.

![preview](./img/prev_Playlist.png)

## Available colors
<p align="center">
<img src="./img/Colors.png" width="300" height="auto" align="center">
</p>


## Installation

It's recommended to find and install this theme on the [Spicetify Marketplace](https://github.com/CharlieS1103/spicetify-marketplace).<br> 
Which will also allow you to set scheme color in the app, without requiring a Spicetify reboot.


**Linux and MacOS** in Bash:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/Mrfunreal/Monolith
```

**Windows** in Powershell:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/Mrfunreal/Monolith
```

**Changing schemes manually**
```Powershell
spicetify config current_theme Monolith
spicetify config color_scheme XXXXXX
spicetify apply
```
Replace XXXXXX with whichever color combination you would like. Eg. `spicetify config color_scheme Red-Orange`
