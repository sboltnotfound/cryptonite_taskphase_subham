# Practising Piping

# Redirectiong Output
using > redirecting from stdout to a file named college.

# Redirecting more output
similar to last question, just the output of a command needed to redirected.

# Appending output
pretty simple, >> appends instead of creating new files.

# Redirecting errors
< redirects std input, 1> redirects std output, 2> redirects std error, where the numbers are called File Descriptor. simple problem just did what it asked to.

# Redirecting input
using < just redirect input from another while which had echoed output.

# Grepping stored results
after redirection, use grep to get that flag.

# Grepping live output
petty cool, 
output of this side | pipes to this side's input
pretty simple question with some cool operator.

# Grepping errors
oo, using "FD>&FD" we can convert from one file descriptor to another. which can then be piped.

# duplicating piped data with tree
Initialy i tried piping the output to a new file, but it said i am trying to use tee instead of /challenge/college (i later realised in tee commands need piping), then i piped the output of the new file to /challenge/college and then catted the file it said the argument --secret [secrect args] to be used. after using those args i got the flag. i like tee.

# writing to multiple programs
using <(command), its pretty simple problem.

# split-piping stderr and stdout
i used /challenge/hack > >(/challenge/planet) 2> >(/challenge/the) to get the flag, didnt need to use piping.