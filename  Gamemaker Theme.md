### What is this?

This gist just includes my GameMaker IDE Code Editor theme. The theme was originally just throwing 
together some colours, but I thought it looked kinda alright! Storing this here firstly so I don't 
lose it, but if you like it for whatever reason, read below to set it up!

#### Installing it! 

##### Code Editor 1

The current code editor for GM stores preferences in your `local_settings.json` file:

- **Windows:** `%appdata%\GameMakerStudio2\<username>_<user_id>\local_settings.json`
- **MacOS:** `~/.config/GameMakerStudio2/<username>_<user_id>/local_settings.json`
- **Linux:** no idea, haven't checked! might be also in `.config`?

Basically just paste the lines into your JSON file, being 
careful not to make duplicates (it's not the most fun process)

##### Code Editor 2

Code Editor 2 has made its way out in the [latest 2024.400 Beta](https://releases.gamemaker.io/release-notes/2024/400) 
(as of writing), and as such I ported the theme over - the new editor now uses
textmate for colourization and is thus a lot more powerful, but its definitely a 
finicky process still; not helped by the old editor storing colours in reverse 
order, where the new one does it more normally.

The **.tmTheme file** is below. Place that in the `Themes` subdirectory under the
same one shown for `local_settings.json` earlier, and on a restart the IDE should pick it up.

You can now select the theme from the dropdown in **Preferences > Code Editor 2 > Theme**. the IDE
may need a restart before it correctly applies.

#### Late Addition!

I've also just gone ahead and ported over the
[Palenight](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme)
theme from VSCode, which I've found I quite like looking at. So that's here too now!
