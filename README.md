# Agate

Maintained fork of the original Agate theme for Obsidian. Agate is a light,
minimal theme built around translucent layers, strong typography, and adjustable
accent/background colors.

> Please turn on *Settings* > *Appearance* > *Translucent window* !

<img src="./img-00.png">

- This is a minimal theme that creates various atmospheres using the overlapping effect of transparent layers.
<img src="./img-01.png">

- I focused extensively on typography to ensure smooth readability.
<img src="./img-02.png">

#### Adjust Color
- You can adjust the accent and background colors using this CSS snippet.
```css
body {
	/* change accent color */
	--accent-color: 55, 0, 255;

	/* change background color */
	--light-color: 170, 170, 170;
	--light-alpha-color: 0;
}
```

- examples
<img src="./img-03.png">
<img src="./img-04.png">

## Manual installation

1. Download `manifest.json` and `theme.css` from the latest GitHub release.
2. Create this folder in your vault: `<vault>/.obsidian/themes/Agate`.
3. Place `manifest.json` and `theme.css` in that folder.
4. Restart Obsidian, then choose **Agate** in **Settings > Appearance > Themes**.

This is a theme, not an Obsidian plugin. It does not need files such as
`main.js` or `styles.css`.
