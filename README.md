# milan-fish-plugin

A personal Fish shell plugin for Milan.

## Functions

- `l` — `eza -l` (long listing)
- `ll` — `eza -lah` (long listing, all files, human-readable sizes)
- `gbda` — Delete all branches merged into HEAD, including squash-merged ones (`--gone` flag deletes branches tracking gone remotes)

## Requirements

- [eza](https://github.com/eza-community/eza) must be installed (`brew install eza`)

## Installation

```sh
fisher install milansuk/milan-fish-plugin
```
