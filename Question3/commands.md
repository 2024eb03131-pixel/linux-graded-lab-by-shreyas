# Question 3 – Links and Disk Usage Commands

## 1. File Creation
echo "This is sample data for link testing." > sample_data.txt

## 2. Hard Link Creation
ln sample_data.txt sample_hard.txt

## 3. Symbolic Link Creation
ln -s sample_data.txt sample_soft.txt

## 4. Inode Verification
ls -i sample_data.txt sample_hard.txt sample_soft.txt

## 5. Inode Analysis
stat sample_data.txt
stat sample_hard.txt
stat sample_soft.txt

## 6. File Metadata Inspection
ls -l sample_data.txt

## 7. Disk Usage Check
du -sh ~

## 8. File Size Overview
ls -lh ~

## 9. Link Deletion Test
rm sample_soft.txt
ls sample_data.txt

## 10. Disk Utility Demonstration
du -h --max-depth=1 ~
df -h
