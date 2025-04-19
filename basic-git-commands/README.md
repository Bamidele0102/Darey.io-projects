# Collaborative Website Development with Git and GitHub

In this mini project, we'll create a step-by-step project to simulate the
workflow of Tom and Jerry using Git and GitHub. This hands-on project
will include installation of Git, setting up a GitHub repository, cloning the
repository, creating branches, making changes, and merging those
changes back into the main branch.

## Part 1: Setup and Initial Configuration

### Step 1: Install Git

- **Windows**: Download the Git installer from [git-scm.com](https://git-scm.com/download/win) and run it.

  - Git was installed successfully and confirmed by running `git version` in the terminal.

![git-version](/basic-git-commands/images/git-version.png)

### Step 2: Create a Git Repository

A Github repository was created with the name ai-startup-website
![github-repo](/Darey.io-projects/basic-git-commands/images/repo-create.png)

![git-repo-created](/Darey.io-projects/basic-git-commands/images/git-repo-created.png)

### Step 3: Clone the Repository

- In the terminal, I created a directory named `git project`. I navigated into it, and then cloned the repository into the directory.

![git-clone](/Darey.io-projects/basic-git-commands/images/git-cloned.png)

- I navigate into the cloned repository.

![navigate-dir](/Darey.io-projects/basic-git-commands/images/navigate-dir.png)

- I created an index.html file in the cloned repository.
![index-html](/Darey.io-projects/basic-git-commands/images/create-file.png)

- I added content to the index.html file.
![index-html-content](/Darey.io-projects/basic-git-commands/images/input-file.png)

- I checked the changes made has not been staged for commit.

![git-status](/Darey.io-projects/basic-git-commands/images/git-status.png)

- I added the changes to the staging area.
  
![git-add](/Darey.io-projects/basic-git-commands/images/git-add.png)

- I checked the status again to confirm the changes have been staged.

![git-status](/Darey.io-projects/basic-git-commands/images/git-status2.png)

- I committed the changes with a message.

![git-commit](/Darey.io-projects/basic-git-commands/images/git-commit.png)

- Then I pushed the main branch to GitHub.

![git-push](/Darey.io-projects/basic-git-commands/images/git-push.png)

## Part 2: Simulating Tom and Jerry's Work

### Tom's work

- I checked the branch I am currently working on.

![git-branch](/Darey.io-projects/basic-git-commands/images/git-branch.png)

- I created a new branch for Tom's work.

![git-branch-create](/Darey.io-projects/basic-git-commands/images/git-checkout-tom.png)

- I checked the branch again to confirm I am on the Tom's branch.

![git-branch-check](/Darey.io-projects/basic-git-commands/images/git-branch2.png)

- I edited the index.html file to add Tom's content.

![tom-content](/Darey.io-projects/basic-git-commands/images/edit-file.png)

- I checked the status to confirm the changes have not been staged.

![git-status](/Darey.io-projects/basic-git-commands/images/git-status3.png)

- I added the changes to the staging area.

![git-add2](/Darey.io-projects/basic-git-commands/images/git-add.png)

- I checked the status again to confirm the changes have been staged.

![git-status4](/Darey.io-projects/basic-git-commands/images/git-status4.png)

- I committed the changes with a message.
![git-commit2](/Darey.io-projects/basic-git-commands/images/git-commit2.png)

- I pushed the Tom's branch to GitHub.
![git-push2](/Darey.io-projects/basic-git-commands/images/git-push-tom.png)

### Jerry's work

- I switched back to the main branch.

![git-checkout-main](/Darey.io-projects/basic-git-commands/images/git-checkout-main.png)

- I pulled the latest changes from the remote repository to ensure I have the latest version of the main branch.

![git-pull](/Darey.io-projects/basic-git-commands/images/git-pull-update.png)

- I created a new branch for Jerry's work.

![git-branch-jerry](/Darey.io-projects/basic-git-commands/images/git-switch-jerry.png)

- I staged Jerry's changes to the index.html file and commited them with a message.

![git-commit-jerry](/Darey.io-projects/basic-git-commands/images/git-add-commit-jerry.png)

- I pushed Jerry's branch to GitHub.

![git-push-jerry](/Darey.io-projects/basic-git-commands/images/git-push-jerry.png)
