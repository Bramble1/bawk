# bawk
AWK program to create and manage aliases in .bashrc

Awk is a text-processing language.

# instructions

to print aliases bawk manages

./bawk l

to add new alias

./bawk a

to reset and init the bashrc file 

./bawk i


# setup

chmod o+x (if not already) then cp to /usr/bin and then call from anywhere with "bawk..."


# future updates

1. Allow user the option to enter custom alias as opposed to just the default 1-5 range(Which is a deliberate design choice), However it means we will
need to keep track of the custom alises
