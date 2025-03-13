# Pandas sales data
sales data transformation

𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧:
 
You are working as a Data Engineer for a company. The sales team has provided
you with a dataset containing sales information. However, the data has some missing values
that need to be addressed before processing. You are required to perform the following tasks:

1. Load the following sample dataset into a PySpark DataFrame ?

2. Perform the following operations ?

a. Replace all NULL values in the Quantity column with 0.
b. Replace all NULL values in the Price column with the average price of the existing data.
c. Drop rows where the Product column is NULL.
d. Fill missing Sales_Date with a default value of '2025-01-01'.
e. Drop rows where all columns are NULL.



# Git hub steps for workflow

1. create a new branch
    ```sh
    git checkout -b <new-branch-name>
    ```
2. checkout the new branch
    ```sh
    git checkout <new-branch-name>
    ```
3. add a file
    ```sh
    git add <file-name>
    ```
4. commit the file
    ```sh
    git commit -m "Add new file"
    ```
5. push the branch
    ```sh
    git push origin <new-branch-name>
    ```
6. create a pull request
    (This step is done on the GitHub website)
7. merge the pull request
    (This step is done on the GitHub website)

8. delete the branch
    ```sh
    git branch -d <new-branch-name>
    ```
9. checkout the master branch
    ```sh
    git checkout master
    ```
10. pull the changes
     ```sh
     git pull origin master
     ```
11. delete the local branch
     ```sh
     git branch -d <new-branch-name>
     ```
12. delete the remote branch
     ```sh
     git push origin --delete <new-branch-name>
     ```
13. end