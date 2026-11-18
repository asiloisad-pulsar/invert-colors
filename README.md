# invert-colors

Invert view colors for images, editor, and PDF viewer. Useful for dark themes or reducing eye strain.

> [!NOTE]
> This package is in maintenance mode. If you use [Lumine](https://github.com/lumine-code/lumine), you may be interested in [invert-colors](https://github.com/lumine-code/invert-colors).

## Features

- **Workspace inversion**: Invert colors of the entire workspace.
- **Editor inversion**: Invert colors of text editors only.
- **Image inversion**: Invert colors of `<img>` and `<canvas>` elements.
- **PDF support**: Invert open and newly created pdf-viewer instances without changing pdf-viewer's global configuration.
- **Animated transitions**: Smoothly transition into and out of inverted modes while respecting reduced-motion preferences.
- **Status bar icons**: Optional per-mode toggle buttons in the status bar.

## Installation

To install `invert-colors` search for [invert-colors](https://web.pulsar-edit.dev/packages/invert-colors) in the Install pane of the Pulsar settings or run `ppm install invert-colors`. Alternatively, you can run `ppm install asiloisad-pulsar/invert-colors` to install a package directly from the GitHub repository.

## Commands

Commands available in `atom-workspace`:

- `invert-colors:workspace`: toggle workspace inversion,
- `invert-colors:editor`: toggle editor inversion,
- `invert-colors:image`: toggle image inversion,
- `invert-colors:pdfviewer`: toggle PDF viewer inversion.

## Contributing

Got ideas to make this package better, found a bug, or want to help add new features? Just drop your thoughts on GitHub. Any feedback is welcome!
