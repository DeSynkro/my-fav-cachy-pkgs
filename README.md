# my-fav-cachy-pkgs

I made this script to help me quickly install my favorite packages on any CachyOS machine. It's my personal pick-list of packages, wrapped in a clean TUI.
Whether it's for my own machines or for friends finally leaving Windows behind, this script gets a fresh system loaded with everything I actually use.

Built with a little help from opencode.

Current version: **1.1** (run `./my-fav-cachy-pkgs --version`). Release notes in [CHANGELOG.md](CHANGELOG.md).

Distributed under the [GNU General Public License v3.0](LICENSE).

![thumbnail](thumbnail.png)

## Usage

```bash
./my-fav-cachy-pkgs
```

Arrow keys to navigate, Tab to toggle packages, Enter to review and install.

## Features

- One menu for official repos, AUR (via paru), and Flatpaks
- Installed packages dimmed with `[installed]` badge
- Dark gray background, so it stays readable on transparent terminals
- Confirmation step before any system changes
- sudo used only for actual installation

## Packages by source and category

Packages are grouped two levels deep: source first, then category.

### CachyOS Repo (47)

| Category | Count |
|---|---|
| Media Production | 8 |
| Media Playback | 3 |
| Browsers & Comms | 5 |
| File Transfer | 4 |
| Gaming | 5 |
| Productivity | 2 |
| Containers & Dev | 3 |
| Backup & Disks | 4 |
| Desktop & Utilities | 5 |
| GPU & Display | 3 |
| Security | 3 |
| Remote & Network | 2 |

### AUR (14)

| Category | Count |
|---|---|
| Gaming | 3 |
| Media & Photos | 3 |
| AI & Notes | 3 |
| Remote & Sync | 1 |
| Utilities | 4 |

### Flatpak (2)

| Category | Count |
|---|---|
| Permissions | 1 |
| Media | 1 |
