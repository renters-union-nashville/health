# Nashville Tenant Union - Health Module

[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/yhatt/marp-cli-example)

## See published slide deck

- <img src="https://icongr.am/octicons/mark-github.svg" width="24" height="24" valign="bottom" /> **[GitHub Pages]**: https://yhatt.github.io/marp-cli-example

## How to write

For Marp slide deck features, please see the documentation of [Marpit Markdown](https://marpit.marp.app/markdown), [the features of Marp Core](https://github.com/marp-team/marp-core#features), and the default example in [`PITCHME.md`](https://raw.githubusercontent.com/yhatt/marp-cli-example/master/PITCHME.md) for .

You have to install [Node.js](https://nodejs.org/) and run `npm i` at first if you want to write slide deck with [Marp CLI].

### Edit deck

Just edit **[`PITCHME.md`](./PITCHME.md)**!

#### Preview deck

**[Marp for VS Code]** extension is the best partner for writing Marp slide deck with live preview.

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode">
    <img src="https://raw.githubusercontent.com/marp-team/marp-vscode/master/docs/screenshot.png" width="500" />
  </a>
</p>

**You can try edit and preview on the web now!** Open https://github.dev/yhatt/marp-cli-example/blob/master/PITCHME.md or hit <kbd>.</kbd> key on this repository, and install [Marp for VS Code] extension.

[marp for vs code]: https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

#### Preview via CLI

```bash
npm run start
```

It will be opened preview window via installed Google Chrome, and track change of `PITCHME.md`.

### Assets and themes

- `assets` directory can put your assets for using in the deck. (e.g. Image resources)
- `themes` directory can put [custom theme CSS](https://marpit.marp.app/theme-css). To use in the deck, please change `theme` global directive.

### Build deck via CLI

```bash
npm run build
```

The built assets will output to `public` folder.

#### Build per assets

```bash
npm run deck      # Output static HTML to public/index.html
npm run og-image  # Output image for Open Graph to public/og-image.jpg
```

## LICENSE

[WTFPL](/LICENSE)
