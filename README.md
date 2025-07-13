# Monolith

A sleek and simple theme for Spicetify.<br> 
Most everything is dark, with some colorful highlights, the color of shich you can modify.

![preview](./img/prev_Playlist.png)

## Available colors
<p align="center">
<img src="./img/Colors.png" width="300" height="auto" align="center">
</p>

## Notable features
- Removes "Playlist Preview/Summary".
- Removes laggy video reccomendations on bottom of home screen.
- Removes "shortcuts" on top of home screen. (Functionally same as"Jump back in" and "Recently played", but keep rearranging. Annoying)
- Removes "Popular" reccomendations.
- "Jump back in" and "Recently played" now appear side by side to save space.
- Font changed to "Noto Sans" for nicer readability.
- Thinner scrollbars.
- Wider and thicker progress bar.
- "Currently playing" song in playlist has background, border, and bigget font. So you find it better.
- "Currently playing" and "Currently looked at" items in library now have background and new icons.
- Lyrics screen fitts theme, instead of using random background color.
- More compact playlist header without color backdrop.
- "Like" and "unlike" playlists of checkmark replaced with generic spinner. Animation could not be recolored with spicetify limitations.
- "Currently Playing" song on bottom left has border around cover art, song name bigger and colored.
- Playing songs in playlist screen got new equalizer animation. Svg based anim.
- Paused songs in playlist screen got new "Waiting" animation. Svg based anim.
- Always shows "Add to playlist" icon on playlists that aren't yours. (Looks odd to have intermitten checkmarks and nothing else.)
- "Now playing" sidebar only shows song info and "About artist". No more queue, merch, tour, credits. (Merch, and Tour data are on artist page anyways.)




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

# Preview images.
![preview](./img/Library.png)