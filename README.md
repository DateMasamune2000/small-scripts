# small-scripts

A collection of small scripts for use on UNIX-based systems

| Name | Description | Dependencies | Notes |
|-|-|-|-|
| `prj` | `tmux` workspace management tool | `tmux` | Requires a text file called `.tmux_projects` in the home directory |
| `readbook` | Brings up a list of books to read | `dmenu` | Parent dir needs to be in `PATH` to work properly with subfolders |
| `readman` | Brings up a list of manual pages to read | `dmenu` | None. Works perfectly. |
| `readrfc` |Brings up a list of RFCs to read. Converts them from HTML to PDF. | `dmenu`, RFC docs | Unreliable, Debian-specific |
| `wallchange` | Selects books to read | `dmenu`, `feh` | Only does `bg-fill`. Manually patch for other styles |
