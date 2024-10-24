# Pondering PATH

# The PATH variable
simple question, just had to set PATH="", then run the run challenge.

# Setting PATH
pretty simple just had to set path to that directory and then viola flag is ours.

# Adding Commands
pretty good question, had to make a script with name 'win' which invoked cat /flag, and had to add the home/hacker directory to path as thats where my win was.

# Hijacking Commands
this was very good question, i initially tried making a new script just for 'rm' which did nothing as the question name is 'hijacking commands' which is a pretty good hint. then i noticed still win was not executing, then i looked at the /challenge/run file and saw that it was never executing win, and i didn't had perms for writing in it, so i had a crazy idea what if instead of rm doing nothing, what if rm only cats the flag, i did that and it worked lol.