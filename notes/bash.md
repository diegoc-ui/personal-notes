# bash

- `set -euo pipefail` makes scripts fail fast.
- `${VAR:-default}` for fallback values.
- `command -v foo` checks if a binary exists.
- `mapfile -t arr < file` reads a file into an array, line per element.
- `shopt -s globstar` lets `**` match across directories.
- `trap 'cleanup' EXIT` runs cleanup whether the script succeeds or fails.
- `<(cmd)` is process substitution: pass cmd's output as a file path.
- `trap 'cleanup' EXIT` runs cleanup whether the script succeeds or fails.
- `coproc` starts a coprocess with bidirectional pipes.
