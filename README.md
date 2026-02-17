# JennsAHDHtools

Small browser-based tools that help me wrangle my brain when ADHD chaos mode is active.

## Current tools (more might appear if I stay on task)

### `prioritymatrix.html`
A single-file **pairwise priority matrix** for figuring out what to do first without overthinking it for 45 minutes.

- Click a decision cell to cycle winner: **column task → row task → clear**
- Edit each task’s short name directly in the row header
- See a live ranked vote list on the right
- Reset all decisions with **RESET**
- Save/load your board with **EXPORT JSON** / **IMPORT JSON**

### `certposter.html`
A certification matrix poster with filters and search so you can quickly scan cert options.

### `timeruler.tex`
A tiny printed guide to help prioritize and track time in 6-minute increments (tenths of an hour), especially useful for consulting time tracking.

This one is partly based on Ruri Ohama's method of prioritization. Check her out: https://www.youtube.com/c/RuriOhama

## Quick start

No build step and no dependencies are required.

1. Clone this repo
2. Open `prioritymatrix.html` or `certposter.html` in a browser
3. Edit/build `timeruler.tex` in your preferred LaTeX workflow

Optional (local server):

- Python: `python -m http.server`
- Then open `http://localhost:8000/prioritymatrix.html` or `http://localhost:8000/certposter.html`

## Project status

Small personal utility project. PRs and issues are welcome for focused improvements and bug fixes.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

See [SECURITY.md](SECURITY.md).

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

Released under the [MIT License](LICENSE).
