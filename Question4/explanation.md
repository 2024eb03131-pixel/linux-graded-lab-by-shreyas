# Question 4 – Explanations

## uptime
This command displays how long the system has been running since the last boot along with system load averages.

## ps -u $USER
This command lists all processes currently running under my user account.

## top -u $USER
This command displays real-time CPU usage of processes owned by my user, allowing identification of the highest CPU-consuming process.

## sleep 300 &
This command starts a process in the background that runs for 300 seconds, demonstrating background execution.

## ps -o pid,ni,cmd -u $USER
This command displays process IDs along with their niceness values.

## renice 10 -p <PID>
This command changes the priority of a running process by increasing its niceness value.

## free -h
This command displays memory usage in a human-readable format, including total, used, and available memory.

## df -h ~
This command shows disk usage of the filesystem where the home directory is located.

## echo $SHELL
This command displays the name of the shell currently being used by the user.

## uname -a > system_report.txt
This command redirects system information output into a file named system_report.txt.

## ncdu ~
This command provides an interactive disk usage visualization, showing directory sizes and helping identify space usage.
