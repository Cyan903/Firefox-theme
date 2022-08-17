# Firefox-theme

![code size](https://img.shields.io/github/languages/code-size/CyanPiano/Firefox-theme) ![last commit](https://img.shields.io/github/last-commit/CyanPiano/Firefox-theme)

My Firefox [userChrome.css](https://www.userchrome.org/) file. This theme has been completely rewritten for modern Firefox. All of the bloat code has been removed. Objects have also been split and restructured.

<img src="https://raw.githubusercontent.com/CyanPiano/Static-github/main/firefox-theme/firefox-rewrite.png" />


**IMPORTANT:** This only works with the Firefox default dark theme. Make sure to change your theme in `about:addons`.

#### To edit...
```
$ npm start watch # watch sass and build on change
````
Simply open the [browser toolbox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) to modify `userChrome.css`.

#### To compile...
```sh
$ npm build # uncompressed
$ npm build:prod # compressed (recommended)
```

## License

  [MIT](LICENSE)
