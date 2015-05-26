# Do More

### I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI.

`$export PATH=$PATH:/usr/local/bin`

# Alternative "english" ways of asking for your working directory

### What is your shell set to?

`$env | grep SHELL`

My shell is set to `SHELL=/bin/bash`

### What directory are you in (don't use pwd this time)?

`$env | grep PWD`

`PWD=/Users/ryansmyth/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_21`

### What is your home directory set to?

`$env | grep HOME`

`HOME=/Users/ryansmyth`

### Can you set your environment to have DEBUG set to true?

`$export DEBUG=true`
