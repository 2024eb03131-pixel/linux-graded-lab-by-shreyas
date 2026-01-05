# Question 2 – Explanations

## mkdir ~/documents
This command creates a directory named documents inside my home directory. It is used to organize project-related files.

## cd ~/documents
This command changes the current working directory to the documents folder so files can be created inside it.

## touch plan.txt
This command creates an empty file named plan.txt inside the documents directory.

## echo "Complete initial project setup and review requirements." > plan.txt
This command writes sample project-related text into the plan.txt file, replacing any existing content.

## ls -l plan.txt
This command displays file permissions, ownership, size, and modification time. The output confirms that my username owns the file.

## cp plan.txt plan_copy.txt
This command creates a duplicate of plan.txt named plan_copy.txt in the same directory.

## mv documents project_documents
This command renames the documents directory to project_documents to better reflect the project scope.

## mkdir ~/project_documents/archive
This command creates a subdirectory named archive inside project_documents for storing older files.

## mv ~/project_documents/plan_copy.txt ~/project_documents/archive/
This command moves plan_copy.txt into the archive subdirectory for proper file organization.

## ls -R ~/project_documents
This command lists all files and subdirectories recursively, showing the complete directory structure.

## realpath ~/project_documents/archive/plan_copy.txt
This command displays the absolute path of plan_copy.txt after it has been moved to the archive directory.
