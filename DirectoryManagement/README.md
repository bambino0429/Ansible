# Directory Management

Directory Permissions
  1. create_dir: Creates a directory named foo with permission mode 0777
  2. remove_p: Removes the directory permissions of group and others to 0744
  3. change_p: Changes the directory permission to 0755

File Permissions
  1. create_file: Creates a file foo.txt in foo directory with 0777
  2. remove_pof: Removes the permissions of the file to 0700
  3. change_pof: Changes the directory permission to 0755

\# | Permission | rwx
---|------------|----
7 | read, write and execute | rwx
6 | read and write | rw-
5 | read and execute | r-x
4 | read only | r--
3 | write and execute | -wx
2 | write only | -w-
1 | execute only | --x
0 | none | ---
