# Question 2 – Linux File and Directory Management

## 1. Project Workspace Setup
mkdir documents

## 2. File Creation
cd documents
touch plan.txt

## 3. Content Addition
echo "Complete initial project setup and review requirements. by shreyas Javalkar" > plan.txt

## 4. File Metadata Verification
ls -l plan.txt

## 5. File Duplication
cp plan.txt plan_copy.txt

## 6. Directory Renaming
cd ~
mv documents project_documents

## 7. Archival Structure
mkdir ~/project_documents/archive

## 8. File Organization
mv ~/project_documents/plan_copy.txt ~/project_documents/archive/

## 9. Recursive Listing
ls -R ~/project_documents

## 10. Path Verification
realpath ~/project_documents/archive/plan_copy.txt
