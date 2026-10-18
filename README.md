# SAD CI/CD Activity 3

**In this activity, the objectives are as follows:**
1. Create a Git Repository on Github
2. Synchronize a local repository with GitHub 
3. Utilize basic Git commands
   - `git add`
   - `git commit`
   - `git push`
   - `git pull`
4. Create and switch between branches using `git branch` and `git checkout`
5. Synchronize local and remote repositories 
   
## 1. Creating a Feature Branch

To create a branch:

```
git branch feature-branch
```
![Screenshot reference for my Git and GitHub
activity](images/3cicd1.jpg)

To check branches:

```
git branch
```
To switch to the branch:
```
git checkout feature-branch
```
To confirm the current branch:
```
git branch
```
Indication of current branch:
```
* feature-branch
```
![Screenshot reference for my Git and GitHub
activity](images/3cicd2.jpg)

## 2. Modify and Commit Changes to Text File

- Open git-activity.txt, update information, and save using `Ctrl + S`
- Stage changed file using `git add git-activity.txt
  `
- Commit change using `git commit -m "Update .txt in feature-branch"` 
  ![Screenshot reference for my Git and GitHub
activity](images/3cicd3.jpg)
- Switch back to main using `git checkout main`
  
### 3. Branch Merging

To merge feature-branch into main:
```
git merge feature-branch
```
![Screenshot reference for my Git and GitHub
activity](images/3cicd4.jpg)

### 4. Pulling and Synchronizing

- Modifying repository `git-activity.txt` file directly on Github
- Committing changes into `main` branch
- Pulling lastest changes from Github using `git pull origin main`  
  ![Screenshot reference for my Git and GitHub
activity](images/3cicd5.jpg)