# Monolith

A sleek and simple theme for Spicetify.<br> 
Most everything is dark, with some colorful highlights, the color of which you can modify.
<div class="grid" markdown>
<img src="./img/prev_Playlist.png" width="auto" height="440"> <img src="./img/Colors.png" width="auto" height="440">
</div>

# Preview images
<details><summary>Expand me ♫</summary>
<img src="./img/liked.png">
<img src="./img/library.png" width="300" height="auto">
</details>

## Notable features
- General:
	- Font changed to "Noto Sans" for nicer readability.
	- Your own avatar on top right is larger.
	- Profile images on user pages are now square.
	- Thinner scrollbars.
	- Liked songs playlist has new image, fitting scheme (gradient with heart icon).
	- Lyrics screen fitting theme.
	- Like and Unlike checkmark anims swapped for basic wait circle. (Couldn't be recolored, Hardcoded to be green, Looked odd.)
	- "Now Playing" sidebar only shows song data and artist data. No more queue, merch, tour, credits, or redundand buttons.
- Home screen:
	- Removed "Shortcuts" on top of home screen.
	- Removed "Jump Back in".
	- Removed laggy video section on bottom.
	- Removed "Popular" reccomendations.
- Track list
	- Header section compacted down, no background color.
	- Removed "Preview/Summary" button.
	- Currently playing song is highlighted in accent color.
	- Unavailable songs are highlighted dark red.
	- Playing song has new equalizer. Waiting anim when paused. Both SVG anims.
	- Always shows "Add to playlist" icon on playlists you do not own.
- Library
	- Note icon (♫) displayed on currently playing library item.
	- Eye icon (👁) displayed on currently looked at library item.
	- Artist images are now square.
	- Text sidebar more compact (from 32px to 26px height )
	- Collapse/Expand library button is always shown, and doesn't slide around anymore. Too distracting
- Player section
	- Track info on bottom left has border arounf cover art and stylized coloring.
	- Progress bar wider and way thicker.
	- Removed useless little dot under active option (Crossplay, Lyrics, Ect) The buttons are colored, why the dots?.
- Search result page
	- Removed Profiles, Audiobooks, Episodes and Podcasts. The top header still has filters to view just those.<br>
Main results are only "Featuring x", Artists, Albums, Playlists, and "Genres & Moods" is available.

## Notes
- Modified "Loopy loop" queue points to fit new progress bar.

## Known Issues
- "Add to library" wait circle _might_ attach to elements added by extensions, and scale is a little off for "like playlists"

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


