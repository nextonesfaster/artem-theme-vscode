<p align="center">
  <a href="https://ariuspys.github.io/artem-theme-vscode/">
    <img alt="artem banner" src="https://i.ibb.co/Cv3vV6y/Artem-Banner.png">
  </a>
</p>

---

Artem is a dark Visual Studio Code theme based on the popular [Horizon Theme](https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode). Artem combines Horizon's amazing UI with a different, brighter set of colors.  

---

<p align="center">
  <!-- marketplace version -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Arius.artem">
    <img alt="marketplace version" src="https://img.shields.io/visual-studio-marketplace/v/Arius.artem?maxAge=3600&style=for-the-badge&colorA=1C1E26&colorB=77b6d4">
  </a>
  <!-- downloads -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Arius.artem">
    <img alt="downloads" src="https://img.shields.io/visual-studio-marketplace/d/Arius.artem?maxAge=3600&style=for-the-badge&colorA=1C1E26&colorB=77b6d4">
  </a>
  <!-- rating -->
  <a href="https://marketplace.visualstudio.com/items?itemName=Arius.artem">
    <img alt="rating" src="https://img.shields.io/visual-studio-marketplace/stars/Arius.artem?maxAge=86400&style=for-the-badge&colorA=1C1E26&colorB=77b6d4">
  </a>
</p>


## Previews

<p align="center">
  Preview HTML
  <img alt="preview-1" src="https://i.ibb.co/NNnYQGs/html-rounded.png">
  Preview - Python
  <img alt="preview-2" src="https://i.ibb.co/FbDc1DK/python-rounded.png">
</p>

## Installation

1. Open the **Extensions** sidebar in VS Code  
2. Search for `Artem Theme`  
3. Click **Install**  
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`  
5. Select **Preferences: Color Theme** and choose Artem.  
6. Enjoy! 🎉  

## Personalization

Tastes change all the time. Fortunately, VS Code makes it easy to customize just about every aspect of your editor.
If you want to change something, open the **Command Palette** and select **Preferences: Open Settings (JSON)**. Here, you can override VS Code's defaults or Horizon's colors.
Check out some of the personalization options below to customize Horizon to suit your taste.

_For more info on theming, visit the [Theme Authoring Guide](https://code.visualstudio.com/api/extension-capabilities/theming) and [Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)._

### Sidebar Contrast

```json
"workbench.colorCustomizations": {
  "activityBar.background": "#1E2028",
  "activityBar.border": "#1E2028",
  "sideBar.background": "#1E2028",
  "sideBar.border": "#1C1E26"
}
```

### Italics

The normal theme only uses italics in a few places: comments, parameters, and some special keywords (e.g. `this`). If you would prefer no italics at all, you can configure this in your settings...

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "No italics",
      "scope": ["comment", "variable.language", "variable.parameter"],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```

### Tag Brackets `<>`

For gray rather than light blue brackets around HTML tags...

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "HTML tag brackets",
      "scope": ["punctuation.definition.tag"],
      "settings": {
        "foreground": "#BBBBBB"
      }
    }
  ]
}
```

## Contributing

### [Code of Conduct](CODE_OF_CONDUCT.md)

Always try your best to make a positive impact on this project and its community. By participating, you are expected to uphold the Code of Conduct.

### [Contributing Guide](CONTRIBUTING.md)

Read the contributing guide to learn about how you can report issues and contribute to changes.

## Credits

* Theme UI - [Horizon Theme](https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode)  

* Logo Image - [Graphic Springs](https://www.graphicsprings.com/logographics/gsentertainment21-1)  

* Logo Font - [Have Heart by Sam Parrett](https://creativemarket.com/SamParrett)

## License

[MIT](LICENSE) © [Jonathan Olaleye](https://github.com/jolaleye)  
[MIT](LICENSE) © [Sujal Bolia](https://github.com/ariuspys)  
