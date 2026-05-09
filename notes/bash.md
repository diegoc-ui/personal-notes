# bash

- `set -euo pipefail` makes scripts fail fast.
- `${VAR:-default}` for fallback values.
- `command -v foo` checks if a binary exists.
- `mapfile -t arr < file` reads a file into an array, line per element.
- `shopt -s globstar` lets `**` match across directories.
