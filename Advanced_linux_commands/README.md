# Advanced Linux Commands

## File Permissions and Access Rights

### chmod command

The `chmod` command allows you to modify file permissions. You can use
both symbolic and numeric representations to assign permissions to the
user, group, and others.

#### How it works

- Create an empty file:

![Create an empty file](./images/touch_file.png)

- Check the file permissions:

![Check the file permissions](./images/ls_latr.png)

- Update the file permissions using `chmod`:

![Update the file permissions using chmod](./images/chmod.png)

- Using the numeric representation:

![Using the numeric representation](./images/chmod_numeric.png)

![Using the numeric representation-2](./images/chmod_numeric_2.png)

### chown command

The `chown` command allows you to change the ownership of files,
directories, or symbolic links to a specified username or group.

#### How chown works

- Create a user:

![Create a user](./images/adduser.png)

- Grant the user sudo privileges:

![Grant the user sudo privileges](./images/usermod.png)

- Switch to the new user:

![Switch to the new user](./images/switch_user.png)

- Modify user account, by changing user's password:

![Modify user account, by changing user's password](./images/passwd.png)

- Switch between users:

![Switch between users](./images/switch_users.png)

- Create a group:

![Create a group](./images/groupadd.png)

- Verify the group:

![Verify the group](./images/groupadd-2.png)

- Add the user to the group:

![Add the user to the group](./images/usermod-2.png)

- Verify the user is added to the group:

![Verify the user is added to the group](./images/groups.png)

- Delete the user:

![Delete the user](./images/userdel.png)

- Change group ownership of a directory:

![Change group ownership of a directory](./images/chown-group.png)

- Change group permissions of a directory:

![Change group permissions of a directory](./images/chmod-group.png)

## Side Task

- Create a group on the server and name it `devops`

![Create a group on the server and name it devops](./images/groupadd-new.png)

- Create 5 users `["mary", "mohammed", "ravi","tunji", "sofia" ]`, and ensure each user belong to the devops group

![Create 5 users](./images/useradd-mary.png)

![Create 5 users-2](./images/useradd-users.png)

- Create a folder for each user in the `/home` directory. For example `/home/mary`.

![Create a folder for each user in the /home directory](./images/user-home-dir.png)

- Ensure that the group ownership of each created folder belongs to "devops"

![Ensure that the group ownership of each created folder belongs to "devops"](./images/group-owner.png)

- Verify the group ownership of each created folder belongs to "devops"

![Verify the group ownership of each created folder belongs to "devops"](./images/verify-group.png)
