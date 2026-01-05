# Question 4 – System Monitoring and Process Management

## 1. System Uptime Verification
uptime

## 2. User Process Listing
ps -u $USER

## 3. CPU Usage Analysis
top -u $USER

## 4. Background Process Execution
sleep 300 &

## 5. Process Priority Management
ps -o pid,ni,cmd -u $USER
renice 10 -p <PID>
ps -o pid,ni,cmd -p <PID>

## 6. Memory Usage Monitoring
free -h

## 7. Disk Space Inspection
df -h ~

## 8. Shell Identification
echo $SHELL

## 9. Output Redirection
uname -a > system_report.txt

## 10. Disk Usage Visualization
ncdu ~
