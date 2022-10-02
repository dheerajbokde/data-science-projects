# Git and GitHub Commands

### 1. init 
- to initialized the working directory
```git
Example: git init
```
![image](https://user-images.githubusercontent.com/5664029/193440940-330169db-5992-481f-912e-c1b0e317346b.JPG)


### 2. clone 
- to clone the existing git repository
```git
Example: git clone https://github.com/dheerajbokde/data-science-projects.git
```
![image](https://user-images.githubusercontent.com/5664029/193441181-7b2eb47a-2628-4c0e-b63f-1aad2c2095ec.JPG)

### 3. config 
- to configure your name and email for user's identity on any repository commit
```git
Example: 
git config --global user.name "your_name"
git config --global user.email "sample@gmail.com"
```
![image](https://user-images.githubusercontent.com/5664029/193441396-c7f331b4-3574-47b9-b744-d0c8c9d8b38a.JPG)

### 4. pull 
- to bring changes from remote repo into local and merge the change into your local repo
```git 
Example: git pull
```
![image](https://user-images.githubusercontent.com/5664029/193441575-7361da29-3f0a-48ef-b7de-bb4c9b21ea92.JPG)

### 5. branch
- to list all the branches in a repository
```git
Example: git branch
```
![image](https://user-images.githubusercontent.com/5664029/193442141-92a3ff5e-5fc2-4b5c-83e6-668f1df61cb2.JPG)

### 6. branch <branch_name>
- to create a new branch named "branch_name"
```git
Example: git branch ast_git
```
![image](https://user-images.githubusercontent.com/5664029/193442193-059ddd59-9e73-44f0-a7be-dca6d9a0aebf.JPG)

### 7. checkout
- to switch branches or restore index and the files in the working tree
```git
Example: git checkout ast_git
```
![image](https://user-images.githubusercontent.com/5664029/193442249-1ed3237e-2776-4acf-bfdf-652e78a4bc90.JPG)

### 8. status 
- to list stagged/unstagged changes that you’ve made but not yet committed
```git
Example: git status
```
![image](https://user-images.githubusercontent.com/5664029/193441637-5e172a94-8704-4d5f-adec-2efa8ee34ed7.JPG)

### 9. add 
- to stage the contents of all/selected files under the current directory
```git 
Example: 
git add . #to stage all changes
```
![image](https://user-images.githubusercontent.com/5664029/193441993-6fa81df3-c37a-44c5-85e8-20aecea813f9.JPG)
```git 
Example: 
git add assignmets/README.md #to stage one or multiple files
```
![image](https://user-images.githubusercontent.com/5664029/193442025-b20e3202-92b5-4c65-9fc0-8ddacdbb8e2d.JPG)

### 10. restore
- to unstage or even discard uncommitted local changes
```git
Example: git restore assignmets/README.md
```
![image](https://user-images.githubusercontent.com/5664029/193442361-e8bf19d4-aeeb-49e2-bc5c-f459c5137f69.JPG)

### 11. commit 
- to permanently store the contents of the index with a meaningful message
```git
Example: git commit -m "added assignments readme"
```
![image](https://user-images.githubusercontent.com/5664029/193442042-d22a923e-659f-45e1-ac93-af1ecb998110.JPG)

### 12. push 
- to push the committed changes to remote repository
```git
Example: git push origin main
```
![image](https://user-images.githubusercontent.com/5664029/193442082-9aa5275e-45c8-4d0c-9b4f-1f8bc718d57a.JPG)

### 13. fetch
- to bring changes from remote repo and allow us to review and resolve any
conflict and after that we can manually commit the new changes
```git
Example: git fetch origin
```
![image](https://user-images.githubusercontent.com/5664029/193442778-a20db54f-2905-4f79-ac3c-989e27d6de9d.JPG)
