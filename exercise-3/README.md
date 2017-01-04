# Exercise-3

In the space below, provide some information about a terminal command you've learned thus far in the class. In particular, you should include the following:

- A _heading_ with the name of the command;
- An example of how it can be used (formatted as a code block);
- A _list_ of information about the command (i.e., things that it does, or how it can be used).

Note that you can preview this Markdown in Atom to make sure it works correctly. See `complete` branch for an example.

---
#CHMOD

This allows you to modify a users permissions on a file or directory

``` chmod 77 file1.txt ```

gives all permissions to the user on this file.

-Deny execute permission to everyone:
chmod a-x file

-Allow read permission to everyone:
chmod a+r file

-Make a file readable and writable by the group and others:
chmod go+rw file

-Make a shell script executable by the user/owner:
$ chmod u+x myscript.sh

-Allow everyone to read, write, and execute the file and turn on the set group-ID:
chmod =rwx,g+s file 
