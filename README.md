# Selenized Light Python Theme for VS Code

The goal of the Selenized Light Theme is to have a good light theme for VSCode inspired by PyCharm themes.   
For text, unlike for video, white background is better for my eyes, that's why this theme will remain light theme.  

Inspired from [nparamonov](https://www.github.com/nparamonov/vscode-cold-python-theme/) great Cold Python theme.    
 

![example](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/example.png)

I hope this theme will be the one you enjoy working with day and night.

## Features

- Full support for syntax
  - Python
  - JSON
  - markdown

- Icons theme, inspired by JetBrains ([https://jetbrains.design/intellij/resources/icons_list/](https://jetbrains.design/intellij/resources/icons_list/)) + folders icons
- JetBrains Mono font ready to use (included in icon theme)

### Syntax theme

Some examples of syntax highlighting

Python

![Python syntax](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/syntax_example_python.png)

JSON

![JSON syntax](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/syntax_example_json.png)


### Icon theme

#### Folders icons

![Folders icons](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/folders_icons.png)

#### File extensions icons

![File extensions icons](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/file_extensions_icons.png)

#### File names icons

Icons for reserved file names

![File names icons](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/file_names_icons.png)

### IDE theme

The colors of various parts of the VS Code interface have also been defined.

For example, the terminal colors match the overall theme color scheme:

![Terminal example](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/terminal_example.png)

Check out the new git diff colors:

![Terminal example](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/git_diff_example.png)

And many other elements have also been transformed, there is not enough space here to show everything.

## Install

Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme) and click on the "Install" button.

### Color theme

Set Color Theme ([guide](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme))

![Select the Color Theme](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/select_color_theme.jpg)

This will give you IDE and syntax highlighting.

If the brackets in your code are highlighted in different colors, you can turn off bracket pair colorization so that the brackets are always the color of the main text.

To do this, add the following line to your settings.json file:

```json
"editor.bracketPairColorization.enabled": false,
```

### File icon theme

Set File Icon Theme ([guide](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-file-icon-theme))

![Select the File Icon Theme](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/select_file_icon_theme.jpg)

This will give you file icons shown in the File Explorer and tabbed headings

### Font

It is recommended to use [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font with the Cold Python Theme.

VS Code doesn't provide clear functionality for adding a custom font to a theme... But I managed to add the font to the File icon theme!

> **Important! To use the JetBrains Mono font, the File Icon Theme must be set!**

Then there are 2 ways to enable the new font:

#### Settings UI

![Change font in settings UI](https://raw.githubusercontent.com/r3gis3r/vscode-selenized-light-python/main/img/change_font_settings_ui.jpg)

> **It is very important to specify the font family exactly `JetBrainsMono`, without spaces!**

#### settings.json file

Add the following line to your settings.json file:

```json
"editor.fontFamily": "JetBrainsMono, Consolas, 'Courier New', monospace",
```

#### Extras

Also, there are some additional settings that you can apply both in the Settings UI and in settings.json file:

```json
"editor.fontSize": 13,
"editor.fontLigatures": true, // ">=" to "≥" etc
"terminal.integrated.fontFamily": "JetBrainsMono",
"terminal.integrated.fontSize": 13,
```

## Recommended extensions

Not all syntaxes are supported in VS Code out of the box. However, you can install extensions that add support for some languages.

There are the extensions below that add support for some syntaxes that have colors defined in the Cold Python Theme:

- [Better DockerFile Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-dockerfile-syntax)
- [Better Jinja](https://marketplace.visualstudio.com/items?itemName=samuelcolvin.jinjahtml)
- [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)

## Credits

I express my deep gratitude to the JetBrains team for their work. Here are links to open resources used to create the Cold Python theme:

- JetBrains icons: [https://jetbrains.design/intellij/resources/icons_list/](https://jetbrains.design/intellij/resources/icons_list/)
- JetBrains Mono font: [https://www.jetbrains.com/lp/mono/](https://www.jetbrains.com/lp/mono/)
