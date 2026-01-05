# Question 2 – Explanations

## whoami
This command was used to display the currently logged-in user. The output confirms that I am operating under my own login account.

## groups
This command lists all groups associated with my user account. It verifies the access groups assigned to my user.

## pwd
This command displays the present working directory. It confirms the current location in the filesystem.

## ls -l
This command lists all files and directories in long format. It shows permissions, ownership, size, and modification time.

## echo "Linux user environment verified" > user_info.txt
This command creates a file named user_info.txt and writes a confirmation message into it, verifying the user environment.

## cat user_info.txt
This command displays the contents of user_info.txt to confirm the file was created correctly.

## wc -m user_info.txt
This command counts the number of characters in user_info.txt. It is used to verify file integrity.

## man mkdir
This command opens the manual page for mkdir. The -p option allows creation of parent directories without errors if they already exist.

## ls ~
This command lists the contents of the home directory. The output is sorted alphabetically by default.

## grep "admin" log.txt
This command searches for the word "admin" in the file log.txt and displays only matching lines.

## uname -r
This command displays the Linux kernel version currently running on the system.

## ping -c 4 www.google.com
This command sends four ICMP packets to google.com to verify network connectivity.

## uptime
This command shows how long the system has been running, the number of logged-in users, and the system load average.
