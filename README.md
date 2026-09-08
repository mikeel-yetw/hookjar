# hookjar

A handful of React hooks I keep copy-pasting between projects

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Install

```bash
npm install
npm test
```

## What it does

- Tiny: no dependencies besides React
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
```
