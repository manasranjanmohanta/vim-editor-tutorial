# vim-editor-tutorial
- To check whether "vim" is installed or not on your system, type the below command in your terminal: <br>
	`vim`  or `vim --version`
- If you type the command in the terminal:
    `vimtutor` <br>
	    (It will open the editor details sections where all commands are given on how can you use Vim editor.)

## How to install vim?
  - To install Vim we will use "brew"(It is a package manager for macOS (and Linux too). It is used to install (and remove) software programs for the terminal or command line. 
  - If you don't have brew installed in your system follow the [steps](https://brew.sh/) to install it.
  - After installing brew, in terminal type: `brew install vim`

  ## How to open file in vim editor?
  - After installation you can open file vim editor by simply typing the below command in terminal: <br>
    `vim <file-name>`

  ## What is vim editor?
  - Vim is model text editor. It has 4 modes: <br>
  1. NORMAL mode : This is the mode where you maximum time will stay, here you can show the content which are present in that file. <br>
  2. INSERT mode : Here you can insert/write contents into the file. <br>
  3. VISUAL mode : In this mode you can highlight a specific lines and then you can perform different operations on them. <br>
  4. COMMAND mode : Here you can basically type your all commands. (By clicking colon(:) on your keyboard you can switch to COMMAND mode.

  ## Basic Commands :
  - To go into INSERT mode press `i` key on your keyboard. (then you can make changes or write into the current file)
  - To exist from the INSERT mode press `esc` key on your keyboard.
  - To save/write the current file press `:w`
  - To exist/quit from the vim editor press `:q`
    You can write and quite at the same time by pressing `:wq`

## Motions
#### Arrows
  - In Vim, normal arrow/cursor keys (←↓↑→) work as expected. However, for touch-typers, it's easier to use the h,j,k,l alternative keys. On a typical keyboard, they're located next to each other on the same row, and easily accessible using right hand. The mnemonic 
  technique to remember which is which among them goes like this:

  1. h/l — those are located "most to the left/right" among the four letters on the keyboard, so they are equivalent to "going left/right"    respectively; <br>
  2. j — lowercase "j" has its tail going "down" below typical letters, like a small arrow - so it's equivalent to "going down"; <br>
  3. k — conversely, lowercase "k" has its "ascender" going "up" above typical letters, like a small pointer - so it's equivalent to "going   up".


  #### Basic motions
- All commands below should be done in normal mode.

| Command      | Description                                                                    |
|--------------|--------------------------------------------------------------------------------|
| h or left    | Go [count] characters to the left                                               |
| j or down    | Go [count] characters below                                                     |
| k or up      | Go [count] characters above                                                     |
| l or right   | Go [count] characters to the right                                               |
| gg           | Go the first line, or [count]'th line, if given                                 |
| H            | Go to the first line in the visible screen                                       |
| M            | Go to the middle line in the visible screen                                      |
| L            | Go to the last line in the visible screen                                        |
| G            | Go the last line, or [count]'th line, if given                                   |
| Home or 0    | Go to first character of the line                                                |
| ^            | Go to first non-blank character of the line                                      |
| +            | Go down one line to first non-blank character                                    |
| -            | Go up one line to first non-blank character                                      |
| $ or End     | Go to the end of the line (if [count] is given, go [count - 1] lines down)       |
| \|           | Go to the [count]'th character or go to the beginning of the line if count not specified |
| f{char}      | Go to [count]'th occurrence of {char} to the right inclusive                     |
| F{char}      | Go to [count]'th occurrence of {char} to the left inclusive                      |
| t{char}      | Go to [count]'th occurrence of {char} to the right exclusive                      |
| T{char}      | Go to [count]'th occurrence of {char} to the left exclusive                      |
| ;            | Repeat latest f, t, F or T [count] times                                        |
| ,            | Repeat latest f, t, F or T, in the opposite direction, [count] times              |
| w            | Go to the beginning of the next word                                             |
| b            | Go to the beginning of the previous word                                         |
| e            | Go to the ending of the next word                                                 |
| ge           | Go to the ending of the previous word                                             |
| %            | Go to matching pairs, e.g (), [], {}, /* */ or #if, #ifdef, #else, #elif, #endif |
| { }          | Previous/next paragraph                                                          |
| [{]}         | Beginning/ending of block                                                         |
| '{char}      | Go to mark (mark with m{char})                                                   |
| <C-B><C-F>   | Previous/next page                                                               |
| <C-O><C-I>   | Go back or forward in the "jump list" (requires jumplist feature, see :help jumps) |
| dd           | To delete the current line                                                       |
| u            | To undo the current operation                                                    |
| ^r           | To redo the current operation                                                    |
| i            | Insert on the left side of the cursor                                            |
| a            | Insert on the right side of the cursor                                            |


## How to go to VISUAL mode?
- To go to the visual mode press : `v` <br>
- Then select by pressing `w` and `y` to copy and then `p` to paste it(but it will paste in the same line)
-  (shift + p) : go to VISUAL LINE mode , then `y` to copy and `p` to paste it(then it will paste in the newline every time)
- To search word press : `/<word you want to search>`
   


    
