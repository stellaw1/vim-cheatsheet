# Vim Cheatsheet

One command a day, keeps the confusion away. 

## File
| Command       | Usage             |
| ------------- | ----------------- |
| :q            | Quit              |
| :q!           | Quit without save |
| :wq           | Save & Quit       |

## View
| Command       | Usage             |
| ------------- | ----------------- |
| Ctrl + v      | Visual mode       |
| Ctrl + f      | Page down         |
| Ctrl + b      | Page up           |
| :set number   | Show line numbers |
| :set nonumber | Hide line numbers |

## Visual mode
| Command       | Usage                  |
| ------------- | ---------------------- |
| Ctrl + v      | Visual mode            |
| =             | Indent lines           |
| V             | Select line            |
| y             | Copy                   |
| d             | Delete                 |
| ~             | Switch case            |
| u             | Set lowercase          |
| U             | Set uppercase          |

## Edit
| Command       | Usage                                      |
| ------------- | ------------------------------------------ |
| R             | Replace mode                               |
| .             | Repeat last change                         |
| u             | Undo                                       |
| Ctrl + r      | Redo                                       |
| i             | Insert                                     |
| r             | Replace one character                      |
| s             | Replace one character + enter Insert mode  |
| c             | Change (movement + enter Insert mode)      |
| a             | Append at cursor                           |
| A             | Append at end of line                      |
| x             | Delete                                     |
| X             | Backspace                                  |
| dd            | Delete line                                |
| dw            | Delete word                                |
| d$            | Delete to end of line                      |
| cc            | Delete line & enter Insert mode            |
| cw            | Delete word & enter Insert mode            |
| c$            | Delete to end of line & enter Insert mode  |
| yy            | Copy line                                  |
| p             | Paste                                      |
| o             | Insert new line below (edit mode)          |
| J             | Join line below                            |

## Navigate
| Command       | Usage                                |
| ------------- | ------------------------------------ |
| `.            | Go to last change in file            |
| H             | Top of screen                        |
| M             | Middle of screen                     |
| L             | Bottom of screen                     |
| w             | Forward (word)                       |
| W             | Forward (word + puntuation)          |
| e             | Forward (end of word)                |
| E             | Forward (end of word + punctuation)  |
| b             | Backward (word)                      |
| B             | Backward (word + punctuation)        |
| %             | Matching bracket                     |
| [{            | Beginning of function body           |
| }]            | End of function body                 |

## Page
| Command       | Usage                          |
| ------------- | ------------------------------ |
| 0             | First column                   |
| ^             | First non blank character      |
| $             | Last column                    |
| gg            | Beginning of file              |
| G             | End of file                    |

## Indent
| Command       | Usage                          |
| ------------- | ------------------------------ |
| >>            | Tab indent                     |
| <<            | Unindent                       |
| ==            | Indent                         |

## Search
| Command       | Usage                          |
| ------------- | ------------------------------ |
| /key          | Searches for "key" word        |
| n             | Next "key" word                |
| N             | Previous "key" word            |
