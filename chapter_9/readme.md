# Do More

### Unix: Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

`$mkdir tmp`

`$cd tmp`

`$touch iamcool.txt`

`$cd ..`

`$rmdir tmp`

`rmdir: tmp: Directory not empty`

I received this error because there is a file in the tmp directory.

# Alternative "english" ways of asking you to create a file

### Can you touch blah.txt?

Yes I can by runnig the following:

`$touch blah.txt`

### Let's create foo.txt

I will do that by running the following command:

`$touch foo.txt`

### Explain what happens if you touch an existing file

If you touch an existing file it will update the time it was last modified.

`$ls -lR`

total 0
-rw-r--r--  1 ryansmyth  staff  0 **May 25 00:35** iamcool.txt

`$touch iamcool.txt`

`$ls -lR`

total 0
-rw-r--r--  1 ryansmyth  staff  0 **May 25 00:46** iamcool.txt
