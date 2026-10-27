# Git rerere

- `rerere` stands for Reuse Recorded Resolution and helps Git remember how merge conflicts were resolved
- When a similar conflict occurs again, Git can reuse the previously recorded resolution
- It can be enabled using `git config --global rerere.enabled true`
- It is useful when repeatedly merging or rebasing branches with similar conflicts