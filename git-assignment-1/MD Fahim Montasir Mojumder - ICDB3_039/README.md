

# Git Workflow Documentation

## 1. Configure Git User Details
Set up your Git user name and email:

```bash
git config --global user.name "fahim000"
git config --global user.email "fahimmontasir74@gmail.com"
```

---

## 2. Generate SSH Key
To connect with GitHub using SSH, generate an SSH key pair:

```bash
ssh-keygen
```



## 3. Initialize a Git Repository
Navigate to your project folder and initialize a Git repository:

```bash
git init
```

This command creates a new Git repository.



## 4. Stage Files for Commit
Add files to the staging area:

```bash
git add .
```

This stages all the changes in your directory.

---

## 5. Commit Changes
Commit the staged files with a message:

```bash
git commit -m "Test commit one"
```



## 6. Rename the Default Branch to Main
Set your default branch name to `main`:

```bash
git branch -M main
```

---

## 7. Add Remote Repository
Link your local repository to a remote repository on GitHub:

```bash
git remote add origin https://github.com/fahim000/silver-octo-guide.git
```

---

## 8. Push Changes to GitHub
Push your committed changes to the remote repository on GitHub:

```bash
git push -u origin main
```

*If you encounter an error regarding no upstream branch, use the following command:*
```bash
git push --set-upstream origin main
```

---

## 9. Clone the Repository
To clone an existing repository, use the following command. Replace the URL with your repository's URL:

```bash
git clone https://github.com/fahime00/scaling-octo-meme.git
```



---

## 10. Add Files and Handle Embedded Repository Warning
After making changes in your repository, you may want to add them to the staging area. If you accidentally add another Git repository inside your main repository, Git will show a warning like this:

**Command:**
```bash
git add .
```


## 11. Commit Changes
To commit the changes, use:

```bash
git commit -m "push after clone"
```

**Example Output:**
```plaintext
[main f854dde] push after clone
 1 file changed, 1 insertion(+)
 create mode 160000 scaling-octo-meme
```

---

## 12. Push Changes to GitHub
To push your committed changes to the remote repository, use:

```bash
git push origin main
```




---
