# Vim Cheat-Sheet for Visual Studio Code

## Content

1. [Motion](#basic-motion)
2. [Screen Motion](#screen-motion)
3. [Word Motion](#word-motion)
4. [Line Motion](#line-motion)
5. [Sentence Motion](#sentence-motion)
6. [Document Motion](#document-motion)
7. [Text Selection](#text-selection)
8. [Search and Replace](#search-and-replace)

### Basic Motion

|     Key      | Description |
| :----------: | :---------- |
| <kbd>h</kbd> | Left        |
| <kbd>j</kbd> | Down        |
| <kbd>k</kbd> | Up          |
| <kbd>l</kbd> | Right       |

### Screen Motion

|     Key      | Description   |
| :----------: | :------------ |
| <kbd>H</kbd> | Top Screen    |
| <kbd>M</kbd> | Middle Screen |
| <kbd>L</kbd> | Botton Screen |

### Word Motion

|             Key             | Description                                     |
| :-------------------------: | :---------------------------------------------- |
| <kbd>w</kbd> , <kbd>W</kbd> | Jump to the first letter of the following word. |
| <kbd>e</kbd> , <kbd>E</kbd> | Jump to the last letter of the following word.  |
| <kbd>b</kbd> , <kbd>B</kbd> | Jump to the first letter of the previous word.  |

### Line Motion

|      Key      | Description                |
| :-----------: | :------------------------- |
| <kbd>0</kbd>  | Jump to start of the line. |
| <kbd>\$</kbd> | Jump to end of the line.   |

### Sentence Motion

|     Key      | Description                        |
| :----------: | :--------------------------------- |
| <kbd>(</kbd> | Jump to the begin of the sentense. |
| <kbd>)</kbd> | Jump to the end of the sentence.   |

### Document Motion

|            Key            | Description                           |
| :-----------------------: | :------------------------------------ |
| <kbd>g</kbd>+<kbd>g</kbd> | Go to the first line of the document. |
|       <kbd>G</kbd>        | Go to the last line of the document.  |
| <kbd>5</kbd>+<kbd>G</kbd> | Go to line 5.                         |

### Text Selection

|             Key              | Description            |
| :--------------------------: | :--------------------- |
|         <kbd>V</kbd>         | Selects entire lines.  |
|         <kbd>v</kbd>         | Selects range of text. |
| <kbd>Ctrl</kbd>+<kbd>v</kbd> | Selects colums.        |

### Search and Replace

|               Command               | Description                                                          |
| :---------------------------------: | :------------------------------------------------------------------- |
| :%s/search_string/replace_string/g  | Search a string in the entire file and replace it.                   |
| :%s/search_string/replace_string/gc | Search a string in the entire file and confirm before replacing text |
