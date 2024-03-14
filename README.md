# Firefox-theme

![code size](https://img.shields.io/github/languages/code-size/CyanPiano/Firefox-theme) ![last commit](https://img.shields.io/github/last-commit/CyanPiano/Firefox-theme)

My Firefox [userChrome.css](https://www.userchrome.org/) theme. A recreation of the old Chrome default dark.

![theme](/assets/rewrite.png)

**IMPORTANT:** This only works with the default Firefox dark theme. Make sure to change your theme in `about:addons`.

## Development

With `pnpm` or `docker`:

```sh
$ pnpm run dev
# OR
$ docker compose up
```

Open the [browser toolbox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) to see live changes.

## Building

```sh
$ pnpm run build # compressed
$ pnpm run build:dev # uncompressed
```

## License

[MIT](LICENSE)
