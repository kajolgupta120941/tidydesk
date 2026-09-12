# tidydesk

Small Go tool: declutter ~/Downloads in one command

Side project, maintained when I have time.

## Install

```bash
go build -o bin/ ./...
```

## Features

- Single static binary, no runtime deps
- Skips hidden files and folders by default
- Dry-run prints the plan before moving anything
- Groups files into folders by extension

## How to use

```bash
./bin/tidydesk ~/Downloads --dry-run
./bin/tidydesk ~/Downloads
```

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```
