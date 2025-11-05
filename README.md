# GitLab → GitHub Repository Mirror Project

## Project Overview: 
This project helps you automatically mirror (sync) a repository from **GitLab to GitHub**, ensuring that all your code, commits, and branches are updated in both platforms.
In simple words we can say that this project helps you copy (mirror) your code from GitLab to GitHub automatically. Whenever you push code to GitLab, it will also appear on GitHub.

## Use cases:

1. Keep a safe copy of GitLab code on GitHub.
2. Publish open-source code easily.
3. Have a second copy in case GitLab fails
4. Use GitLab for testing and GitHub for deploymen( CI/CD Integration).

## Features:
1.Automatic Sync

2.One-way Mirror 

3.Easy setup

4.Secure connection

5.Auto updates

6.Backup and visibility

7.Free tool

## How it works:
You push code to GitLab, GitLab automatically copies that code to GitHub, So both have the same project all the time.

### Flow:

 Developer/Local System  -->Push Code -->GitLab Repository--> Auto Morror --> GitHub Repository --> Code Updated -->View On GitHub

 

 ## Steps to Set Up GitLab → GitHub Mirroring

 ### Step 1: Create a  Repository

A. GitLab
- Go to https://gitlab.com
-  Click New Project → Blank Project
- Name it: mirror-repo
- Click Create Project

![](./img/Screenshot%201.png)

B. GitHub
- Go to https://github.com
- Click New Repository
- Name it the same: mirror-repo
- Keep it Public (or Private if preferred)
- Click Create Repository

![](./img/Screenshot%202.png)

### Step 2: Configure Mirroring

- In the URL field, paste your GitHub repository URL.

- Select Push direction (GitLab → GitHub).

- Choose Authentication method:
   - SSH key: Recommended for secure sync.

   ![](./img/Screenshot%203.png

### Step 3: Add Authentication

 Using SSH Key

- Click Generate SSH key in GitLab mirror settings.

- Copy the public key.

- Go to GitHub → Settings → SSH and GPG keys → New SSH key, and paste it.

![](./img/Screenshot%204.png)

### Step 4: Initial Testing: Add, Commit and Push

![](./img/Screenshot%205.png)

![](./img/Screenshot%206.png)

### Step 5: Verify the Sync

- Check your GitHub repository — the commits, branches, and tags should now be visible.

- Future pushes to GitLab will automatically appear on GitHub.

![](./img/Screenshot%207.png)

## Conclusion

The GitLab → GitHub Mirror Project makes it easy to keep your code updated on both platforms.
Once set up, every time you push code to GitLab, it automatically appears in GitHub — without doing any extra work.

In short:

**“Push once to GitLab — your GitHub stays in sync automatically.”**



