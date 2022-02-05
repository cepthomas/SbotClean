# What It Is
Sublime Text plugin to perform some common text clean up.

Built for Windows and ST4. Other OSes and ST versions will require some hacking.

## Commands
| Command                  | Description |
|:--------                 |:-------     |
| sbot_trim                | Line ends ws trim, arg `'how'`:<br/>`'leading'`<br/>`'trailing'`<br/>`'both'` |
| sbot_remove_empty_lines  | Like it says, arg `'how'`:<br/>`'remove_all'`all lines<br/>`'normalize' `compact to one |
| sbot_remove_ws           | Like it says, arg `'how'`:<br/>`'remove_all'`all ws<br/>`'keep_eol'`keep eols<br/>`'normalize' `compact to one ws |

## Settings
| Setting                  | Description |
|:--------                 |:-------     |
| sel_all                  | Option for selection defaults: if true and no user selection, assumes the whole document (like ST) |
