# Do More

### Make 20 more directories and remove them all.

**Creating 20 directories**

`$mkdir -p dir01/dir02/dir03/dir04/dir05/dir06/dir07/dir08/dir/09/dir10/`

`dir11/dir12/dir13/dir14/dir15/dir16/dir17/dir18/dir19/dir20`

**Removing all directories one at a time**

`$cd dir01/dir02/dir03/dir04/dir05/dir06/dir07/dir08/dir/09/dir10/`
     
`dir11/dir12/dir13/dir14/dir15/dir16/dir17/dir18/dir19/`

$ls

dir20

$rmdir dir20

$cd ..

$rmdir dir19

$cd ..

$rmdir dir18

$cd ..

$rmdir dir17

$cd ..

$rmdir dir16

$cd ..

$rmdir dir15

$cd ..

$rmdir dir14

$cd ..

$rmdir dir13

$cd ..

$rmdir dir12

$cd ..

$rmdir dir11

$cd ..

$rmdir dir10

$cd ..

$rmdir dir09

$cd ..

$rmdir dir08

$cd ..

$rmdir dir07

$cd ..

$rmdir dir06

$cd ..

$rmdir dir05

$cd ..

$rmdir dir04

$cd ..

$rmdir dir03

$cd ..

$rmdir dir02

$cd ..

$rmdir dir01

### Make a single path of directories that is 10 deep and remove them one at a time.

**Creating new directories**

$mkdir -p dir01/dir02/dir03/dir04/dir05/dir06/dir07/dir08/dir09/dir10

$cd dir01/dir02/dir03/dir04/dir05/dir06/dir07/dir08/dir09/

$ls

dir10

$rmdir dir10

$cd ..

$rmdir dir09

$cd ..

$rmdir dir08

$cd ..

$rmdir dir07

$cd ..

$rmdir dir06

$cd ..

$rmdir dir05

$cd ..

$rmdir dir04

$cd ..

$rmdir dir03

$cd ..

$rmdir dir02

$cd ..

$rmdir dir01

# Alternative "english" ways of asking you to delete a directory.

### Can you remove the tmp directory?

No. When I ran `rmdir tmp` I received the following error:

`rmdir: tmp: Directory not empty`

### Let's remove the tmp directory.

$cd tmp/stuff/things/frank/joe/alex/

$ls

john

$rmdir john

$cd ..

$rmdir alex

$cd ..

$rmdir joe

$cd ..

$rmdir frank

$cd ..

$rmdir things

$cd ..

$rmdir stuff

$cd ..

$rmdir tmp


