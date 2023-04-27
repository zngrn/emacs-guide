# emacs - A quick guide to getting started and command shortcuts

## Basics

A quick breakdown for abbreviations:

| Legend         | Notes               |
| -----          | -----               |
| C - Ctrl       | control key         |
| M - Option     | meta key/option key |
| s - super      | command key         |
| S - Shift      | shift key           |

### Some key bindings to level up:

| Action                    | Command    |
| ------                    | -------    |
| help                      | C-x C-h    |
| quit                      | C-g        |
| exit                      | C-x C-c    |
| run command               | M-x        |
| switch buffers            | C-x b      |
| cycle buffer - left       | C-x left   |
| cycle buffer - right      | C-x right  |
| kill buffer               | C-x k      |
| **File**                  |  ####      |
| new                       | C-x C-n    |
| open                      | C-x C-f    |
| save                      | C-x C-s    |           
| save as                   | C-x C-w    |            
| **Edit**                  |  ####      |
| undo                      | C-_        |
| redo                      | C-x        |
| kill (cut)                | C-w        | 
| copy                      | M-w        |
| yank (paste)              | C-y        |
| kill region reverse order | M-Y        |
| find                      | C-s `|` C-r|
| find all                  | M-x occur  |
| find & replace            | M-%        |
| replace all               | !          |
| wrap text                 | M-q        |
| **Selection**             |  ####      |
| search forward            | C-s        |
| search reverse            | C-r        |
| mark region (select area) | C-space    |
| **Go**                    |  ####      |
| to file                   |
| to definition             |
| to declaration            |
| to implementation         |
| to references             |
| to line                   |
| **Run**                   |  ####      |
| add breakpoint            |
| toggle breakpoint         |
| run in debug mode         |
| run                       |
| add/edit configuration    | 
| **Window**                |  ####      |
| close active window       | C-x 0      |
| close all but active      | C-x 1      | 
| split window vertically   | C-x 2      |
| split window horizontally | C-x 3      |
| switch windows            | C-x o      |
| ** Point Movement**       |  ####      |
| up a para                 | C-up       |
| down a para               | C-down     |
| next word                 | C-left/rght|
| beginning of line         | home       |
| end of line               | end        |
| **Code**                  |  ####      |
| rename symbol             |
| refactor                  |
| extract to method         |
| **emacs specific**        |  ####      |


### Additional Notes

  * Kill Ring - emacs by default allows to use a clipboard to store all regions copied.
  When yanking, you can select from this collection of clipboard.

  * To search and cycle through results, keep pressing `C-s | C-r`. Akin to terminal usage.

  * Replace all instance works as: M-% `ret` <replacement text> `ret` followed by `!` to replace all.
  To skip an instance you can press `n` instead.

### Thoughts

*Note:* This key bindings listed above will grow over time.

