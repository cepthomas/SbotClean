# What It Is

Sublime Text plugin to perform some common text clean up: removing white space in different ways.

Built for ST4 on Windows and Linux.

## Commands
| Command                    | Type     | Description               | Args                                                                    |
| :--------                  | :------- | :-------                  | :-------                                                                |
| sbot_trim                  | Context  | Remove ws from Line ends  | how = leading OR trailing OR both                                       |
| sbot_remove_empty_lines    | Context  | Like it says              | how = remove_all (all lines) OR normalize (compact to one)              |
| sbot_remove_ws             | Context  | Like it says              | how = remove_all (all ws) OR keep_eol OR normalize (compact to one ws   |

## Settings
| Setting            | Description         | Options                                                               |
| :--------          | :-------            | :------                                                               |
| sel_all            | Selection default   | if true and no user selection, assumes the whole document (like ST)   |
