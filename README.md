# Linux-Notes
learning discoveries 
## Commands I’ve Learned

-'echo' - outputs any provided texts 
- 'whoami' - identifies current logged in user 
- `ls` – lists files
- `cd` – change directory
- `pwd` – print working directory
- `man` – manual/help command
- 'cat' concatenate, is used to view or combine the contents of files 
- 'find' - is used to search for files and directories in a specified location based on name, size, type, modified date, and more 
- 'grep' - is used to search for specific text or patterns inside files
- '&' - run commands in the background so terminal use continues
- '&&' - chains commands, runs second command if first command runs successfully
- '<' - Sends the output to a file, overwriting if the file exists
- '<<' - Append, sends the output to a file, but adds to the end if the file exists
- 'control + l' - clear working terminal screen output
- 'tab' - auto-complete commands, file names, directories
- '|' - pipe take the output of one command and pass it as input to another
- 'rm' - delete or remove directories
- 'chomd' - (change mode) sets who can read, write, or execute a file
    r = read (4)
    w = write (2)
    x = execute (1)
- 'ls -l' - who owns a hidden file
- su - switch user
- /etc (etcetera) - stores critical system wide configuration files
    - /etc/passwd - stores user account info (not passwords) *sha512
    - /etc/shadow - stores encrypted user passwords (only viewable by root) *sha512
    - /etc/crontab - system-wide scheduled tasks (cron jobs)
    - /etc/ssh/ - contains settings for the SSH server and client
    - /etc/hostname/ - system's hostname
    - /etc/hosts - maps hostnames to IP addresses locally
    - /etc/fstab -controlls how drives and partitions are mounted
    - /etc/network or etc/netplan/ - network configurations
 - /var (variable) - stores data that changes while data is running, files that grow, move, or change over time
    - /var/log/ - log files - system messages, errors, etc. (i.e. syslog, auth.log)
    - /var/spool/ - queued tasks (i.e. print jobs, mail)
    - /var/cashe/ - cashed files used by applications
    - /var/tmp/ -  temporary files that persist between reboots
    - /var/lib/ - state information for system services (i.e. package databases, containers)
    - /var/run or /r/ runtime information like active PIDs, sockets (short-lived
- /root - home directory of superuser
- /tmp (temporary) - directory for temporary storage of files, can include automatically delete files 
- nano - text editor
- vim - advanced text editor
- wget- download files from the internet
- SCP (secure copy) - securely copying files between computers over SSH
    - remote cp (copy) but encrypted
    - scp [source] [destination]
    - scp myfile.txt user@remote-ip:/home/user/ (send file to remote machine)
    - scp uer@remote-ip:/home/user/notes.txt ./notes.txt (get a file from your remote machine to your computer)
- 
    - 
