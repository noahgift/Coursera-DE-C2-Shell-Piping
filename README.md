# Coursera-DE-C2-Shell-Piping
Learn to pipe in the shell


An exploration of the Linux Shell

## Goal:   Learn the basics of shell piping

Let's practice some common shell piping operations

### Part 1: Count the files and directories in /usr/bin

1.  Pipe the output of `ls -l /usr/bin | wc -l` to count the files and directories in `/usr/bin`
2.  How many did you count?

### Part 2:  Create a new file with echo a

1.  Run the following command "echo 'hi'"
2.  Pipe this to a file by using "echo 'hi' > hello.txt"
3.  Now run `ls` to verify it exists
4.  count the words in the file `cat hello.txt | wc -w`
