# What It Is
Sublime Text plugin to perform some common text clean up: removing white space in different ways.

Built for ST4 on Windows and Linux.

## Commands
| Command                  | Implementation | Description |
|:--------                 |:-------        |:-------     |
| sbot_trim                | Context        | Remove ws from Line ends, arg `'how'`:<br/>`'leading'`<br/>`'trailing'`<br/>`'both'` |
| sbot_remove_empty_lines  | Context        | Like it says, arg `'how'`:<br/>`'remove_all'`all lines<br/>`'normalize' `compact to one |
| sbot_remove_ws           | Context        | Like it says, arg `'how'`:<br/>`'remove_all'`all ws<br/>`'keep_eol'`keep eols<br/>`'normalize' `compact to one ws |

## Settings
| Setting                  | Description |
|:--------                 |:-------     |
| sel_all                  | Option for selection defaults: if true and no user selection, assumes the whole document (like ST) |
