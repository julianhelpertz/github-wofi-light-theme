# GitHub Wofi Theme

This is a very simple stylesheet collection, which styles the wofi searchbar according to GitHub's light and dark themes.

## Installation
**1.** If you already applied a theme and want to save it, make sure you back up your old stylesheet.  
> `mv ~/.config/wofi/style.css ~/.config/wofi/styleBackUp.css` <br/>
<br/>

**2.** I use [NerdFont](https://www.nerdfonts.com/), so make sure you have the fonts installed.

> [!TIP]
> If you don't want to use NerdFont, the default fallback font is `monospace`. So you have to change nothing. <br/>
> However, you can change the font family in the `*` block at the beginning. <br/>

<br/>

**3.** Download or copy your preferred *"style.css"* from one of the style directories to `~/.config/wofi/` and leave the name *"style.css"* or set the path in the config. <br>

Available styles:
- `style.css` - Default light style  
- `blocky-style/style.css` - Blocky light style
- `lite-style/style.css` - Lite light style
- `dark-style/style.css` - Default dark style
- `blocky-style-dark/style.css` - Blocky dark style  
- `lite-style-dark/style.css` - Lite dark style

<br>

**4.** Aaand you're done. Open wofi with your preferred keyboard binding(mine is Super+Space) and it should look like this: <br><br>

### Default Style
![Image](https://github.com/user-attachments/assets/9928647b-5f96-40cb-bea0-a836c3ed8f0d)

### Blocky Style
![Image](https://github.com/user-attachments/assets/39fcfaff-243c-4a9f-9889-8d75138e1f3e)

### Lite Style
![Image](https://github.com/user-attachments/assets/763c75fb-a4b5-450c-9655-5b581a9ea126)

### Dark Style (Default Dark)
Available in `dark-style/style.css` - A dark version of the default style using GitHub's dark theme colors.

### Blocky Style Dark
Available in `blocky-style-dark/style.css` - A dark version of the blocky style with left border focus and solid selected entries.

### Lite Style Dark  
Available in `lite-style-dark/style.css` - A dark version of the lite style with bottom border focus and minimal selection styling.
