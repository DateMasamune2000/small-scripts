# small-scripts

A collection of small scripts for use on UNIX-based systems

| Name | Description | Dependencies | Notes |
|-|-|-|-|
| `prj` | `tmux` workspace management tool | `tmux` | Requires a text file called `.tmux_projects` in the home directory |
| `readbook` | Brings up a list of books to read | `dmenu` | Parent dir needs to be in `PATH` to work properly with subfolders |
| `readman` | Brings up a list of manual pages to read | `dmenu` | None. Works perfectly. |
| `readrfc` |Brings up a list of RFCs to read. Converts them from HTML to PDF. | `dmenu`, RFC docs | Unreliable, Debian-specific |
| `wallchange` | Changes wallpaper | `dmenu`, `feh` | Only does `bg-fill`. Manually patch for other styles |
| `animegirl` | Brings up a picture of an anime girl holding a programming book | `dmenu`, `feh`, [`Anime-Girls-Holding-Programming-Books`](https://github.com/cat-milk/Anime-Girls-Holding-Programming-Books) | Change variable to point to where you downloaded the repo |
