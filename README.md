# Color Palette Extractor

[![Live demo](https://devilking7x.github.io/color-palette-extractor/badge.svg)](https://devilking7x.github.io/color-palette-extractor/) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

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

## Who it is for

This project is designed for **designers and frontend teams**. Its narrow first release focuses on helping them extract reusable color palettes from local images. The interface uses realistic synthetic fixtures so the value is understandable without connecting a production account.

## Privacy and safety

The default experience is local-first: inputs are processed in the browser or in the user's own development environment, with no required account, API key, payment flow, or remote storage. Fixtures contain synthetic data only. Review a fork's hosting and analytics configuration before using it with sensitive information.

## Validation

The release workflow is intentionally reproducible. Run `pnpm install --frozen-lockfile`, `pnpm check`, and `pnpm build` before submitting a change. Manual review should cover keyboard operation, visible focus, mobile layout, empty states, and both successful and error paths.

## Limitations

This is a focused open-source MVP rather than a hosted replacement for a production system. It does not guarantee business, legal, financial, medical, accessibility, or security compliance by itself. Validate outputs against the context in which you plan to use them.

## License

Released under the [MIT License](LICENSE).
