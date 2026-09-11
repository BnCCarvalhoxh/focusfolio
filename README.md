# focusfolio

MV3 extension playground: page reading-time estimator

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Highlights

- Manifest V3, service worker based
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
