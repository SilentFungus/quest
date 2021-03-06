# Quinn's Utterly Elegant Speedrun Timer

A speedrun timer for \*nix terminals

## Features

- Global hotkeys
- 24-bit terminal color
- Human readable JSON splits file
- Import splits from a Splits.io file
- High fps rendering

## Usage

Copy `examples/sample.json` somewhere, replace the sample information with
the names of your game, categories and segments. Changing the number of
segments after the first use of the split file is currently unsupported.

### Default Keybinds
| Keys | Action                | Global |
| ---- | --------------------- | ------ |
| `R`  | Start                 | YES    |
| `F`  | Stop / Reset          | YES    |
| `E`  | Split                 | YES    |
| `G`  | Undo split            | YES    |
| `V`  | Skip split            | YES    |
| `Q`  | Close                 | NO     |
| `T`  | Toggle global hotkeys | YES    |
| `C`  | Toggle compact UI     | NO     |

Hotkeys can be configured in `$HOME/.config/quest/keymaps/default`

## Third Party Integration

If a feature isn't listed here, it probably isn't planned
yet and may not ever be

### [Splits.io](https://splits.io/)

- [X] Import game, category and segment names from generic format
- [ ]  Import all information the generic format supports i.e. run histories
- [ ]  Export runs in the generic format

### [Speedrun.com](https://www.speedrun.com/)

- [ ] Submit runs
