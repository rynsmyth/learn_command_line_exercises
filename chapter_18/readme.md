# Do More

### Use quotes to find "new file" and "old file" and "This is".

`$grep 'newfile' *.txt`

`$grep 'oldfile' *.txt`

`$grep 'This is' *.txt`

# Alternative "english" ways of asking you to search files:

### Show me the lines in foo.txt that have "ERROR" in them.

`$grep -i 'ERROR' foo.txt`

### Show me the lines in bar.txt that have "davinci" in them.

`$grep -i 'davinci' bar.txt`

### Can you print all the lines in text files that have your first and last name in them?

`$grep -i 'Ryan Smyth' *.txt`

### Use cat > newfile.txt to write some content to newfile.txt

`$cat > newfile.txt`

`This is some added text`

Control + d to save and exit

### Add a comment to the readme.md that explains what the -i option to grep accomplishes.

The -i option to grep will make the search not case sensitive.
