# Do More

### Open your text file again and repeatedly copy-paste the text so that it's about 50-100 lines long.

### Copy it to your temp directory again so you can look at it.

### Now do the exercise again, but this time page through it. On Unix you use the spacebar and w (the letter w) to go down and up. Arrow keys also work. On Windows just hit spacebar to page through.

`$cp ex12.txt ~/Desktop/`

`$cd ~/Desktop`

`$mine ex12.txt`

`$less ex12.txt`

`$more ex12.txt`

### Look at some of the empty files you created too.

`$touch empty_1.txt`

`$touch empty_2.txt`

`$more empty_1.txt`

`$less empty_1.txt`

`$more empty_2.txt`

`$less empty_2.txt`

*The command `$more` seems better for checking that files are empty.*

# Alternative "english" ways of asking for your working directory

### Can we see what's in our production.log?

`$more production.log`

### What does our database.yml look like?

`$less database.yml`
