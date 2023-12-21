## Editors

### Interlude: Buffers, Windows, and Screens

### Vim

##### What is Vim?

Vim is a powerful text editor and key binding set for working with text files. It has been around since the 1970s and is widely used by developers and hobbyist to date.

##### Why use Vim?

- Speed and Efficiency
- Reduced RSI
- Powerful Tool-set
- Vim can be emulated in just about every editor, whether via a plugin or built-in feature, so you can take your skills wherever they lead you.

Essentially, if there is some task you wish to do within a file: Vim can do it, and likely more efficiently than other editors or tools available.

##### The General Idea

Commands...
Modes

##### Getting Started

From the command line run: `vim [filename]`, or open the app on your desktop, if it exists.

After making changes, you can save and quit by typing `:wq` followed by the ENTER key. To save without quitting use just `:w`, or to quit without saving type `:q`. If you are unable to quit because you have unsaved changes that you don't want to save, use `:q!` to quit and discard those changes.

##### Moving around

Move your cursor with `h`, `j`, `k`, `l`. They correspond with movement to the LEFT, DOWN, UP, and RIGHT, respectively. This is the hardest but most crucial command-set to learning Vim. Spend a good amount of time here before moving on.

Notice how when you cross vertically over a shorter line (between two longer lines) that Vim remembers the horizontal position you were at before moving.

Move around by words (groups of characters) with `w`, `b`, `e`. 

- `w` moves the cursor forward by the beginning of words, 
- `b` moves the cursor backwards by the beginning of words, and 
- `e` moves forward by the end of words. 

Each of these commands have a capital-case counter-part (`W`, `B`, `E`) that essentially do the same command except they are strictly whitespace delimited.

Within a line, you can jump to the beginning or end of it with `0` and `$`, respectively. Alternatively, if you want to go to the first non-whitespace character in the line, use `^` instead of `0`.

You can quickly jump to the top or the bottom of a file:

- `gg` to go to the top, and
- `G` to jump to the bottom.

`C-f` and `C-b` allow you to move forward and backward in the file by a full screen height. Also, `C-d` and `C-u` are useful, moving up or down by a half screen height.

If at anytime you entered the wrong movement command, or for any other reason, you want to get back to where you just were a moment ago: `C-o` will take you back to your last position. If you continue to hit `C-o` it will take you back more, through your positional history in the file.

##### Editing Text

So we can move around, but what use is an editor without editing. To begin typing text we have to enter `INSERT` mode

`i` and `a`, and their counterparts `I` and `A`, put your cursor into `INSERT`.
- `i` before the cursor,
- `a` after the cursor,
- `I` at the beginning of the line (ie. `^i`), and 
- `A` at the end of the line.

Also, `o` and `O` are useful for entering `INSERT` mode by opening a new line below or above the current line.

Commands like `dd` delete the complete current line; `C` deletes the current line AFTER the cursor and enters insert mode.

##### Selecting Text

##### Other Common Editor Tasks

`y y` `p`

`u` `C-r`

##### Combining Commands

We've encountered a few command combinations in our brief tour so far: `gg` and `dd`.

`d w` `d j`

`S-v j d` `S-v y j p`

##### Closing

See the cheatsheet in [More Resources](#more-resources) for a full list of available commands. But note: what you can do with Vim far extends the commands listed in the list below, it is the way in which you combine them, extend them, and introduce plug-ins that truly make Vim an every-thing tool.

If still have a taste for what Vim can offer, the next section goes into more use cases and utilities within Vim.

##### More Resources

### Vim, Continued

##### Searching

### Emacs

### VSCode