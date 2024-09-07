# Group_Homes
The main intention for this repo is to generate consistent directory structures that I personally use for resource sharing and role seperation for users on the same system. The permissions for the directories are influenced by hideproc=2, coupled with firejail and in short time will reflect a systemd restriction across dbus to hide a users processes. I'm trying to hide users from numeration, setup segmentation for role specific users, and hide processes from them.

#### Group Home structure
Some of these are reflections of what you'd see when issuing a simple `ls /usr/local`. But, either way, this is the structure:

- Group_Name (I.e., Sudoers, Users, Utils).
  - `./Unit`:
  - `./bin`:
  - `./etc`:
  - `./src`:
  - `./usr`:
    - `./include`:
    - `./lib`:
    - `./share`:
  - `./var`:
    - `./backups`:
    - `./log`:
    - `./opt`:
    - `./tmp`
