0-iam_betty - switches the current user to the user betty.
1-who_am_i - prints the effective username of current user.
2-groups - prints all the groups the current user is part of.
3-new_owner - changes the owner of the file hello to the user betty.
4-empty - creates an empty file called hello.
5-execute - adds execute permission to the owner of the file hello.
6-multiple_permissions - aads execute permission to the owner and the group owner,and read permission to other users, to the file hello.
7-everybody - adds execution permission to the owner, the group owner and the other users, to the file hello.
8-James_Bond - add no permission at all for both the owner and the group and all the permissions for the other users.
9-John_Doe - set the mode of the file hello to -rwxr-x-wx 1 owner group 23 Sep 20 14:25 hello. Notice that the file hello will be in the working directory.
10-mirror_permissions - sets the mode of the file hello the same as olleh's mode which is both the file hello and olleh will be in working directory.
11-directories-permissions - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.here regular files doesn't changed.
12-directory_permissions - creates a directory called my_dir with permissions 751(rwxr-x--x) in the working directory
13-change_group - changes the group owner to school for the file hello100-change_owner_and_group - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
101-symbolic_link_permissions - changes the owner and the group owner of _hello to vincent and staff respectively.
102-if-only - changes the owner of the file hello to betty only if it is owned by the user guillaume.
103-Star_Wars - play the StarWars IV episode in the terminal.  
