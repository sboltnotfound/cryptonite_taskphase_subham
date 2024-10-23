# File Globbing

# Matching with *
used 'cd /ch*' which used globbing to find the challenge directory, then invoked the run command

# Matching with ?
? looks for only 1 character, and we were just restricted to use 'c' 'l' and '*', hence i just removed the c's and l's and inserted ? between them.

# Matching with []
pretty simple, tho i initially thought of using '--' with the argument 'file_[bash]', but removing the -- worked. i wonder when is '--' used for arguments and when its not used.

# Matching paths with []
pretty simple,just add to add path of the files.

# Mixing globs
pretty good question, '[cep]*' glob  would result into challenging, educational, pwning as no other words starting with c,e,p were there.

#Exclusionary globbing
similar to last problem, just the only difference is using '^' to not the search.