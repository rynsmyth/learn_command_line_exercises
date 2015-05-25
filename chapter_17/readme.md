# Do More

###Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

I added this card to my flashcards

###You can put any directory where the . (dot) is. Try another directory to start your search there.

`$find ~/workspace -name "*.txt" -print | less`

###Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

`$find ~ -name "*.mov" -print > movies.txt`

# Alternative "english" ways of asking for your working directory

### Can you show me all the files in slash temp slash?

Yes by running the following command:

`$find /tmp/ -name "*.*" -print`

Which returns the following:

/tmp//com.apple.launchd.uNxWTsogfG
/tmp//com.apple.launchd.WERPNuySg2
/tmp//foo.txt
/tmp//KSOutOfProcessFetcher.501.qQkpPp2uZLdVc5pukHmfJMR4bkM=

### What log files are in your log directory?

`$find log/ -name "*.log" -print`

### Run find in the class directory, pipe the output to pbcopy and create a gist with the content.   Paste the Gist URL as a comment on this story.

`$find ~/workspace/davinci_coders_t2_2015 -print | pbcopy`

<a href="https://gist.github.com/69bbdecb36c3e9832f6d.git">pbcopy</a>
