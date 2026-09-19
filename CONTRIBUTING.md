# Contributing to Color Palette Extractor

Thanks for contributing. Keep image processing local and avoid adding analytics or uploads without a documented privacy review.

## Checks

```bash
pnpm install
pnpm check
pnpm build
pnpm format
```

Test with bright, dark, monochrome, transparent, small, and large images. Check keyboard access, mobile layout, and clipboard fallback behavior when changing UI.

Use focused branches and commits, for example `feat: add perceptual color clustering` or `fix: handle empty canvas data`.

Never commit personal images, generated output, secrets, or user data. Pull requests should explain the user benefit and include a short verification note.
