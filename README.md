
# Variant Dark
Variant Dark is a tweaked version of [Monokai Spectrum Theme](https://vscodethemes.com/e/monokai.theme-monokai-pro-vscode/monokai-pro).

### What Changed?
Not much just except two token colors.

| Token  | Previous Color | New Color | New Color Hex |
| --------  | ------------------- | --------------------- |--------------------- |
| strings | yellow      | green                  | **#00FF7F** |
| numbers      | blue | orange             | **#FF8C00** |


## How to Install.
1. Download zip or clone this repository.
2. You will find a folder `variant-dark`, Inside the folder there are files like `package.json` etc.
3. You will have to put this `variant-dark` folder to your `.vscode/extensions` directory.
4. Select `"Variant Dark"` as your Color Schemes in VS Code Settings.


## Alternative
If you don't want to Install this theme but want the custom token colors, You can add the following settings in your vscode `settings.json` file.
It will work with the offical Monokai Pro Spectrum Theme.

```javascript
"editor.tokenColorCustomizations": {
    "[Monokai Pro (Filter Spectrum)]": {
      "strings": "#00FF7F",
      "numbers": "#FF8C00"
    }
  },
```
