## Linux

| Command                                   | Description                                                 |
| ----------------------------------------- | ----------------------------------------------------------- |
| `df -h /`                                 | Show total free disk space                                  |
| `ls -haltr`                               | list files by date (human readable, reversed)               |
| `du -sh folder`                           | Show size of folder                                         |
| `ls \| wc -l`                             | Number of files in folder                                   |
| `rm -r mydir`                             | Delete folder                                               |
| `cp -avr home/sourcedir home/destinydir`  | Copy folder with all content                                |
| `echo hello > $(date +%Y%m%dT%H%M%S).txt` | Saves output of command in file <br> with timestamp as name |
| `mkdir -p folder/{1..10}`                 | Make 10 subfolders                                          |
| `ctrl + z`                                | suspend running process                                     |
| `ps f`                                    | show processes                                              |
| `fg`                                      | resume stopped process (in foreground)                      |
| `bg`                                      | resume stopped process (in background)                      |
| `jobs`                                    | show jobs                                                   |
| `kill <PID>`                              | kill process with ID <PID>                                  |
| `sleep 360 &`                             | starts sleep command in background                          |
| `cat /etc/os-release`                     | show which linux distro is installed                        |
| `rwx, 421 (e.g. chmod 600 <file>)`        | change permissions                                          |
| `mv/cp <old> <new>`                       | rename/copy  file                                           |
| `ls/rm *.mp3`                                | list/delete all mp3                                                |
| `cd`                                | same as  `cd ~`                                              |
| `pushd` <folder>, `popd`                                  | go into folder, go back where you came from                                            |
| `file song.mp3`                                | shows type of file, here: mp3                                         |
| `locate <file name>`                                | find <file name>                                           |
| `sudo updatedb `                                | update db for locate                                        |
| `cal`                                | show calender                                           |
| `whatis scp`                                | return: secure copy (remote file copy program)                                         |
| `apropos time`                                | show commands related to time                                          |
| `man time`                                | show manual for time                                          |
| `cat >> file, ctrl-d to exit`                                | opens editor and saves what you write in file                                          |
| `cat file1 file2`                                | concatenates files                                          |
| `more/less file2`                                | pager/scroller for file2                                          |
| export PATH=/home/pi/.local/bin:$PATH  | add to path in .bashrc |
|pkill -u [username] | kill all processes belonging to [username]|
|`ifconfig \| grep inet`|get ip|
|`alias l='ls -AF'`                                | alias a comand                                         |

## sudo (linux)

if commands after sudo don't work:

Just remove the PATH reset in /etc/sudoers. It's likely a rule called secure_path
