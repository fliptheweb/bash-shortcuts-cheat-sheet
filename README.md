## Useful bash / zsh shortcuts

MacOS iTerm 2 users must turn on meta key — https://coderwall.com/p/_lmivq

Nice visual cheetsheet from [article](https://clementc.github.io/blog/2018/01/25/moving_cli/): 
![visual cheetsheet](https://github.com/fliptheweb/bash-shortcuts-cheat-sheet/blob/master/moving_cli.png?raw=true)

### Move cursor
<table>
<tr>
<td>Ctrl + a</td>
<td>Go to the beginning of the line (Home)</td>
</tr>
<tr>
<td>Ctrl + e</td>
<td>Go to the End of the line (End)</td>
</tr>
<tr>
<td>Alt + b</td>
<td>Back (left) one word</td>
</tr>
<tr>
<td>Alt + f</td>
<td>Forward (right) one word</td>
</tr>
<tr>
<td>Ctrl + f</td>
<td>Forward one character</td>
</tr>
<tr>
<td>Ctrl + b</td>
<td>Backward one character</td>
</tr>
<tr>
<td>Ctrl + xx</td>
<td>Toggle between the start of line and current cursor position</td>
</tr>
</table>

### Edit
<table>
<tr>
<td>Ctrl + u</td>
<td>Cut the line before the cursor position</td>
</tr>
<tr>
<td>Alt + Del</td>
<td>Delete the Word before the cursor</td>
</tr>
<tr>
<td>Alt + d</td>
<td>Delete the Word after the cursor</td>
</tr>
<tr>
<td>Ctrl + d</td>
<td>Delete character under the cursor</td>
</tr>
<tr>
<td>Ctrl + h</td>
<td>Delete character before the cursor (backspace)</td>
</tr>
<tr>
<td>Ctrl + w</td>
<td>Cut the Word before the cursor to the clipboard</td>
</tr>
<tr>
<td>Ctrl + k</td>
<td>Cut the Line after the cursor to the clipboard</td>
</tr>
<tr>
<td>Alt + t</td>
<td>Swap current word with previous</td>
</tr>
<tr>
<td>Ctrl + t</td>
<td>Swap the last two characters before the cursor (typo)</td>
</tr>
<tr>
<td>Esc + t</td>
<td>Swap the last two words before the cursor.</td>
</tr>
<tr>
<td>Ctrl + y</td>
<td>Paste the last thing to be cut (yank)</td>
</tr>
<tr>
<td>Alt + u</td>
<td>UPPER capitalize every character from the cursor to the end of the current word.</td>
</tr>
<tr>
<td>Alt + l</td>
<td>Lower the case of every character from the cursor to the end of the current word.</td>
</tr>
<tr>
<td>Alt + c</td>
<td>Capitalize the character under the cursor and move to the end of the word.</td>
</tr>
<tr>
<td>Alt + r</td>
<td>Cancel the changes and put back the line as it was in the history (revert)</td>
</tr>
<tr>
<td>Сtrl + _</td>
<td>Undo</td>
</tr>
</table>

### History
<table>
<tr>
<td>Ctrl + r</td>
<td>Recall the last command including the specified character(s)(equivalent to : vim ~/.bash_history). </td>
</tr>
<tr>
<td>Ctrl + p</td>
<td>Previous command in history (i.e. walk back through the command history)</td>
</tr>
<tr>
<td>Ctrl + n</td>
<td>Next command in history (i.e. walk forward through the command history)</td>
</tr><tr>
<td>Ctrl + s</td>
<td>Go back to the next most recent command.</td>
</tr>
<tr>
<td>Ctrl + o</td>
<td>Execute the command found via Ctrl+r or Ctrl+s</td>
</tr>
<tr>
<td>Ctrl + g</td>
<td>Escape from history searching mode</td>
</tr>
<tr>
<td>Alt + .</td>
<td>Use the last word of the previous command</td>
</tr>
</table>

### Process control


### Bang(!)
Bash also has some handy features that use the ! (bang) to allow you to do some funky stuff with bash commands.

<table>
<tr>
<td>!!</td>
<td>run last command</td>
</tr>
<tr>
<td>!blah</td>
<td>run the most recent command that starts with ‘blah’ (e.g. !ls)</td>
</tr>
<tr>
<td>!blah:p</td>
<td>print out the command that !blah would run (also adds it as the latest command in the command history)</td>
</tr>
<tr>
<td>!$</td>
<td>the last word of the previous command (same as Alt + .)</td>
</tr>
<tr>
<td>!$:p</td>
<td>print out the word that !$ would substitute</td>
</tr>
<tr>
<td>!*</td>
<td>the previous command except for the last word (e.g. if you type ‘find some_file.txt /‘, then !* would give you ‘find some_file.txt‘)</td>
</tr>
<tr>
<td>!*:p</td>
<td>print out what !* would substitute</td>
</tr>
</table>

## Recent links
* [Bash Shortcuts For Maximum Productivity](http://www.skorks.com/2009/09/bash-shortcuts-for-maximum-productivity/)
* [Syntax Bashkeyboard](http://ss64.com/osx/syntax-bashkeyboard.html)
