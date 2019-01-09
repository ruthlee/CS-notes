# INTRODUCTION TO VIM

Vim is a text editing tool (like emacs). It's used for workflow efficiency when programming.

Note that you can combine moving and editing commands. For example, dw will delete a word, d$ will delete everything until the end of a line. 

Probably the most important commands: 
 - u : UNDO
 - ctrl+r : REDO
 - zz : moves screen up so that the cursor is in the middle of the screen (ZZ saves and exits vim, be careful!)

Moving Commands:
 - k : move up
 - j : move down
 - h : move left
 - l : move right
 - w : move by a word
 - b : move back by a word
 - $ : to end of line
 - 0 : to beginning of line
 - H M L : to high, middle, low positions
 - shift + arrow : moves by entire words (same as w BUT IN EDITING MODE)

Text editing: 
 - i : start editing mode
 - "escape" : escape editing mode
(Note: editing mode will automatically happen with below commands) 
 - r : replace the thing the cursor is on
 - o O : open new line below/above the current line
 - cw, Cw : correct the token / word following the cursor
 - dd : delete a line
 - yy : copy lines 
 - yw yW : copy tokens / words
 - p : paste the last thing you copied

These are the most important things. Will update as I learn more.  



