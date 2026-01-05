# Question 3 – Explanations

## echo "This is sample data for link testing." > sample_data.txt
This command creates a file named sample_data.txt and writes sample text into it.

## ln sample_data.txt sample_hard.txt
This command creates a hard link to sample_data.txt. Both files point to the same inode.

## ln -s sample_data.txt sample_soft.txt
This command creates a symbolic link that references the original file by name.

## ls -i sample_data.txt sample_hard.txt sample_soft.txt
This command displays inode numbers. The hard link shares the same inode as the original file.

## stat sample_data.txt / stat sample_hard.txt / stat sample_soft.txt
These commands display detailed inode and link information for comparison.

## ls -l sample_data.txt
This command shows file permissions, ownership, size, and timestamps of the file.

## du -sh ~
This command displays the total disk usage of the home directory in human-readable format.

## ls -lh ~
This command lists files in the home directory along with their sizes in human-readable format.

## rm sample_soft.txt
This command deletes the symbolic link without affecting the original file.

## du -h --max-depth=1 ~
This command shows disk usage of each directory inside the home directory.

## df -h
This command displays filesystem disk space usage in a human-readable format.
