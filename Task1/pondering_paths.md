# The Root
just did what the paragraph asked me to - using '/pwn' to invoke the 'pwn' program.

# Program and absolute paths
again just did what the paragraph asked me to - using '/challenge/run' to invoke run program inside challenge folder.

# Position thy self
Intially i used 'ls' in the home/hacker directory and found 'lost+found'. i tried cding to it but it didn't open said i didn't had permission. next i went to home directory and saw only 'hacker' there, next i went to the start using 'cd /' then i saw a 'flag' directory which again said i dont have permissions to open [i tried chmod the permissions but didn't work lol] then i went to challenge folder and that said "incorrect go to 'some location' this location, i went there and used '/challenge/run' and then viola got the flag.

# Position elsewhere
Same solution as position thy self.

# Position yet elsewhere
Again same exact process

# Implicit relative paths from /
Again similar process, just had to use relative path 'challenge/run'

# explicit relative paths, from /
Similar process, just had to use './challenge/run'

# implicit relative path
similar process, just had to go to the directory of challenge then using './run' as directly using 'run' wont be allowed as its a safety measure for not accidentaly running commands [suppose same file and same utility command name]

# Home sweet home!
initially i tried going to smth like /tmp or smth, but relaised it counted '/' as a character as well, so then i had a cool thought what if i pass '~ ' as argument. i did that but it was not reading it back to me and saying its a directory, hence then i tried '~ /~ ' which soled the proble by going to /home/hacker/~.

