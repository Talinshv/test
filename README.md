# **Git and Github Instruction**
## **1. Create Repository and Push from PC**
### **Step 1: In GitHub**
1. Go to Repositories
2. Push new
3. add a name  like (ACA)
4. choose public
5. accept
6. coppy URL
### **Step 2: In PC**
1. Make a new folder like (ACA Talin)
2. Open terminal in the same folder
3. for creating "ACA" folder in "ACA Talin you should add coppied URL in terminal
> git clone 
1. in terminal for changing place to ACA Talin/ACA :
> cd ACA
### **Step 3: In VS Code**
1. Open new folder
2. go to C:/ACA Talin/ACA and push select. So we will have ACA folder in VS Code
3. in VS Code terminal now you are in C:/ACA Talin/ACA
4. For adding text "Data Analitic" in PC folder:
> echo “Data Analitic” > ACA
5. for transferring changes to Github with file name ACA and subject “Add Instruction” with comment “Data Analitic”:
> git commit -m “Add Instruction”
> 
> git push
## **2. Steps for create file in Github and Pull it to VS code**
### **Step 1:In Github**
1. go to add file and create a new file 
2. give a name
3. put comment 
4. push commit changes
### **Step 2: In VS Code**
for adding created file in VS Code:
> git pull