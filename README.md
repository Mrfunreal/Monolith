# Monolith

A sleek and simple theme for Spicetify. 
Most everything is dark, with some colorful highlights, the color of shich you can modify.

![preview](./img/prev_Playlist.png)

## Available colors
![colors](./img/colors.png)



## Installation

**Spicetify Marketplace**

[Spicetify Marketplace](https://github.com/CharlieS1103/spicetify-marketplace) allows you to change the color scheme in-app without rebooting.


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


**Changing schemes**
```Powershell
spicetify config current_theme Monolith
spicetify config color_scheme red-orange
spicetify apply
```

**Changing schemes manually**
```Powershell
spicetify config current_theme Monolith
spicetify config color_scheme XXXXXX
spicetify apply
```
Replace XXXXXX with whichever color combination you would like. Eg. `spicetify config color_scheme Red-Orange`
