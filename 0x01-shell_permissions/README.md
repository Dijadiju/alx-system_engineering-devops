Created a directed for my 0x01-shell_permissions project.

The 0-iam_betty script switches the current user to the user betty.

The 1-who_am_i script prints the effective username of the current user. 

The 2-groups script prints all the groups the current user is part of.

The 3-new_owner changes the owner of the hello file to betty.

The 4-empty creates an empty file called hello.

The 5-execute script changes the file owner  permissions  for the hello file to include execution.

The 6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

The 7-everybody script adds execution permission to the owner, the group owner and the other users, to the file hello.

The 8-James_Bond script sets the hello file to no permissions for the user and group owners and all permissions for othetr users.

The 9-John_Doe sricpt sets the mode of the file hello to -rwxr-x-wx.

The 10-mirror_permissions script sets the mode of the file hello the same as olleh’s mode.

The 11-directories_permissions script dds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

The 12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory.

The 13-change_group script changes the group owner to school for the file hello.

The 100-change_owner_and_group script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

The 101-symbolic_link_permissions script changes the owner and the group owner of _hello to vincent and staff respectively.

The 102-if_only script changes the owner of the file hello to betty only if it is owned by the user guillaume.