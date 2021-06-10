## 0x01-shell_permissions

- This repository contains scripts used to create and change file permissions in Unix-like operating systems

### Description of each script

- **0-iam-betty** - Switches the current user to the user betty.
- **1-who_am_i** -  Prints the effective username of the current user.
- **2-groups** -  Prints all the groups the current user is part of.
- **3-new_owner** -  Changes the owner of the file hello to the user betty.
- **4-empty** -   Creates an empty file called hello.
- **5-execute** -  Adds execute permission to the owner of the file hello.
- **6-multiple_permissions** - Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- **7-everybody** - Adds execution permission to the owner, the group owner and the other users, to the file hello. No commas not allowed to be used.
- **8-James_Bond** - Sets the permission to the file hello as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions
- Not allwoed to use commas
- **9-John_Doe** - Sets the mode of the file hello to ```-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```. No commas allowed.
- **10-mirror_permissions** -sets the mode of the file hello the same as olleh’s mode.
- **11-directories_permissions** - Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
- **12-directory_permissions** - Creates a directory called dir_holberton with permissions 751 in the working directory.
- **13-change_group** -  Changes the group owner to holberton for the file hello.
- **100-change_owner_and_group** -  Changes the owner to betty and the group owner to holberton for all the files and directories in the working directory.
- **101-symbolic_link_permissions** -  Changes the owner and the group owner of _hello to betty and holberton respectively.
- **102-if_only** -  Changes the owner of the file hello to betty only if it is owned by the user guillaume.
- **103-Star_Wars** -  Plays the StarWars IV episode in the terminal.
