# permissions

- 0-iam_betty: switches the current user to betty.
- 1-who_am_i: prints the effective username of the current user.
- 2-groups: prints all the groups the current user is part of.
- 3-new_owner: changes the owner of the file hello to the user betty.
- 4-empty: creates an empty file called hello.
- 5-execute: adds execute permission to the owner of the file hello.
- 6-multiple_permissions: adds execute permission to the owner and group, and read permission to others, on the file hello.
- 7-everybody: adds execute permission to the owner, the group and other users on the file hello.
- 9-John_Doe: sets the mode of the file hello to -rwxr-x-wx.
- 10-mirror_permissions: sets the mode of the file hello to the same mode as the file olleh.
- 11-directories_permissions: adds execute permission to all subdirectories of the current directory for owner, group and others, leaving regular files unchanged.
- 12-directory_permissions: creates a directory called my_dir with permissions 751 in the working directory.
- 13-change_group: changes the group owner to school for the file hello.
- 8-James_Bond: sets the permissions of the file hello to no permissions for owner and group, and all permissions for other users.
