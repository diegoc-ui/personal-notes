# git

- `git switch -c <branch>` to create + switch (newer than `checkout -b`).
- `git restore --staged <file>` undo `git add`.
- `git log --oneline --graph --decorate --all` for a quick view.
- `git switch -` jumps to the previous branch, like `cd -`.
- `git commit --fixup=<sha>` then `git rebase -i --autosquash` for clean history.
- `git diff --staged` shows what's actually going into the next commit.
- `git stash push -m "wip" -- path/` stashes only specific paths.
