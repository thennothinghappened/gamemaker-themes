
### What is this?
Welcome to my collection of GameMaker IDE themes, because I can't seem to settle on one
specifically!

### Themes

#### Orca's Theme (CE1, CE2)
[!](./OrcasTheme.png)

This one I actually made rather than ported. It looks alright, I prefer it to the default colours.

#### Palenight
[!](./PaleNight.png)

This is a port of the
[Palenight](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme)
theme from Visual Studio, which looks quite nice.

#### VSCode 2026 Light
[!](./VSCodeLight2026.png)

I've been preferring light themes recently, and this one is quite pleasant (although it looks
more relaxed with VSCode's font in my opinion.)

#### Installing them!

##### Code Editor 1
The current code editor for GM stores preferences in your `local_settings.json` file:

- **Windows:** `%AppData%\GameMakerStudio2\<username>_<user_id>\local_settings.json`
- **MacOS:** `~/Library/Application Support/GameMakerStudio2/<username>_<user_id>/local_settings.json`
- **Linux:** `~/.config/GameMakerStudio2/<username>_<user_id>/local_settings.json`

Basically just paste the lines into your JSON file, being careful not to make duplicates (it's not
the most fun process)

##### Code Editor 2
Code Editor 2, first released in 2024.400, uses TextMate-style theming specified in XML files,
which is way nicer to deal with than CE1. Colours are also stored in the reverse order to CE1
(i.e., CE2 stores them sanely), which made porting the first theme a pain.

To add any of the CE2 themes here, download the corresponding `.tmTheme` file and place it in your
`Themes` folder, which'll be in the same place your `local_settings.json` lives. Restart the IDE
to pick it up, and find the option in the dropdown at **Preferences > Code Editor 2 > Theme**.

