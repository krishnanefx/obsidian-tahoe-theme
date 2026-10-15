# Contributing to Tahoe

Thanks for helping. Tahoe is a small project made and kept up by one person, so the most useful help is a clear report.

## Bugs, ideas and questions

- **A bug:** [open an issue](https://github.com/krishnanefx/obsidian-tahoe-theme/issues/new/choose) with the bug form. The steps to reproduce it, your Tahoe and Obsidian versions and your device are what make a bug fixable.
- **An idea:** the feature-request form. Say what you were trying to do before how it could work.
- **A question, or help setting it up:** [Discussions](https://github.com/krishnanefx/obsidian-tahoe-theme/discussions).

## Pull requests

Small fixes (a bug, a typo, a clearer sentence) are welcome as pull requests. For anything bigger, open an issue first, so we can agree on the approach before you spend time on it.

Everything is in `theme.css`. Check a change in light and dark mode, and with Tahoe Glass on and off.

- No `:has()` and no `!important` (the community directory's review flags both); use selectors that are specific enough instead.
- Use Obsidian's CSS variables, so plugins' own styles still fit.
- Keep the README's disclosures true: anything new that uses the network, another app, the clipboard or files outside the vault has to be listed there.

By contributing, you agree that your contribution is licensed under the project's [MIT License](LICENSE).
