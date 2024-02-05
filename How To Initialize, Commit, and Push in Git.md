## How To Initialize, Commit, and Push in Git

Several `commands` that we will use :
```
echo "# GitHub" >> README.md
git init
git add README.md
git commit -m "First commit"
git branch -M main
git remote add origin <GitHub repository URL>
git push -u origin main
```

### 1. Choose A Directory as Git Repository
First of all, choose the directory you want to work with Git. If you still didn't made one, then make one first. 
Check "How To Navigate Through Directories and Create New Directory Using Terminal.md" on how to do it.

For example, I make a new directory called "GitHub-Tutorial" that will be used as git repository
![Open profile (7)](https://github.com/RaykiDan/GitHub-Tutorial/assets/90367128/443696f6-c06b-4c5a-8ab7-ae0250bd78ad)

### 2. Create A README.md File
Type `echo "# GitHub" >> README.md`. This command will create a README file which is important for a repository to give information and describe the repository itself.
![Open profile (8)](https://github.com/RaykiDan/GitHub-Tutorial/assets/90367128/a1de7e9c-5d0b-4159-8f6d-4c4f4629eb02)

### 3. Create GitHub Repository And Copy The URL
Create a GitHub repository from GitHub.com, check how to do it in "How To Create Repository.pdf". Copy the given URL in the new repository.
![Open profile (9)](https://github.com/RaykiDan/GitHub-Tutorial/assets/90367128/1c5fa29c-dbc6-4f19-958b-4d433957bd28)

### 4. Initialize Git
In order to make GitHub-Tutorial directoy as a git repository, we need to initialize it first with command `git init`. This command will create a git init file in the directory.
![Open profile (10)](https://github.com/RaykiDan/GitHub-Tutorial/assets/90367128/2eca0c64-573e-44ce-af2f-00c6fb3592e6)

### 5. Add The File(s) To The Working Tree and Commit
Type `git add README.md` to add the README file into the working tree. You can also use `git add .` which will add all directories and files in the working directory into the working tree.
Then, type `git commit -m "First commit"` to add description on your commit upon these files.
