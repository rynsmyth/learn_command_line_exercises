# Do More

### Explain what the argument `-lR` to `ls` does.

The `ls -lR' command shows the directories ,subdirectories and the permissions of their files.

`~workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_6 $ls -lR`

total 8
-rw-r--r--  1 ryansmyth  staff  572 May 24 22:44 readme.md
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 tmp

./tmp:
total 0
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 stuff

./tmp/stuff:
total 0
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 things

./tmp/stuff/things:
total 0
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 frank

./tmp/stuff/things/frank:
total 0
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 joe

./tmp/stuff/things/frank/joe:
total 0
drwxr-xr-x  3 ryansmyth  staff  102 May 23 19:28 alex

./tmp/stuff/things/frank/joe/alex:
total 0
drwxr-xr-x  2 ryansmyth  staff  68 May 23 19:28 john


# Alternative "english" ways of asking for a list of files:

### What's in the tmp directory?

To view what is in my temp directory I would run the command:

`$ls tmp/`

### Can you show me what files are in that directory?

There are no files in `~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_6/tmp`

### What files are in your home directory?

`$ls ~`

There are no files in my home directory just the following directories:

`Applications		Music`

`BitTorrent Sync		Pictures`

`Calibre Library		Public`

`Desktop			RubymineProjects`

`Documents		Sites`

`Downloads		projects`

`Dropbox			ruby-getting-started`

`Library			workspace`

`Movies`

### What's in slash temp?

I ran the following command while in the slash temp directory and it returned the following:

`Ryan-Smyths-MacBook-Pro:tmp ryansmyth$ ls` or `$ls /tmp`

`KSOutOfProcessFetcher.501.qQkpPp2uZLdVc5pukHmfJMR4bkM=`

`com.apple.launchd.WERPNuySg2`

`com.apple.launchd.uNxWTsogfG`

`log`

## *Pivotal Tracker* - What command would you run to see all the files in that directory?

`$ls -R /tmp`
