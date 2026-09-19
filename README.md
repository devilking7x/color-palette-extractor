# Color Palette Extractor

> Turn pixels into a useful palette.

Color Palette Extractor samples an image in your browser and returns five dominant colors as hex values. Copy individual colors or export a ready-to-use CSS custom-properties file.

## Features

- Image picker with drag-and-drop friendly UI.
- Local Canvas API pixel sampling.
- Five dominant color values.
- Click-to-copy hex colors.
- CSS variables export.
- Optional source preview.
- No upload, account, backend, or tracking.

## Getting started

```bash
git clone https://github.com/devilking7x/color-palette-extractor.git
cd color-palette-extractor
pnpm install
pnpm dev
```

```bash
pnpm check
pnpm build
```

## Privacy

The image is read and sampled in browser memory. It is not intentionally uploaded to a server. Use a modified deployment only after reviewing its behavior.

## Tech stack

React, TypeScript, Vite, Canvas API, Tailwind CSS, Lucide React, and pnpm.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md). Accessibility, better color clustering, format support, and documentation contributions are welcome.

## License

MIT — see [LICENSE](LICENSE).

## Demo

Try the live app: https://devilking7x.github.io/color-palette-extractor/
