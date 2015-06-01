# Do More

###Add the * to your deck of flash cards. On the back write: "matches anything in a wildcard like *.txt".

Added `*` command to my flashcards.

# Alternative "english" ways of using the asterisk:

### How big is the foo.txt?

I would run the fllowing command:

`$stat -x foo.txt`

Which returns the following:

  File: "foo.txt"
  
  **Size: 0**            FileType: Regular File
  
  Mode: (0644/-rw-r--r--)         Uid: (  501/ryansmyth)  Gid: (   20/   staff)

Device: 1,4   Inode: 3301229    Links: 1

Access: Mon May 25 14:58:56 2015

Modify: Mon May 25 14:55:15 2015

Change: Mon May 25 14:55:15 2015

### Can you output all the txt files in this directory?

Yes by running the following command:

`$cat *.txt`

### Show me the content of the text files in slash temp.

I would run the following command:



`$cat /tmp/*.txt`

But the files are empty which results in nothing to return
