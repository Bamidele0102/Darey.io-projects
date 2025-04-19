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

![git-version](./images/git-version.png)

### Step 2: Create a Git Repository

A Github repository was created with the name ai-startup-website
![github-repo](./images/repo-create.png)

![git-repo-created](./images/git-repo-created.png)

### Step 3: Clone the Repository

- In the terminal, I created a directory named `git project`. I navigated into it, and then cloned the repository into the directory.

![git-clone](./images/git-cloned.png)

- I navigate into the cloned repository.

![navigate-dir](./images/navigate-dir.png)

- I created an index.html file in the cloned repository.

![index-html](./images/create-file.png)

- I added content to the index.html file.

![index-html-content](./images/input-file.png)

- I checked the changes made has not been staged for commit.

![git-status](./images/git-status.png)

- I added the changes to the staging area.
  
![git-add](./images/git-add.png)

- I checked the status again to confirm the changes have been staged.

![git-status](./images/git-status2.png)

- I committed the changes with a message.

![git-commit](./images/git-commit.png)

- Then I pushed the main branch to GitHub.

![git-push](./images/git-push.png)

## Part 2: Simulating Tom and Jerry's Work

### Tom's work

- I checked the branch I am currently working on.

![git-branch](./images/git-branch.png)

- I created a new branch for Tom's work.

![git-branch-create](./images/git-checkout-tom.png)

- I checked the branch again to confirm I am on the Tom's branch.

![git-branch-check](./images/git-branch2.png)

- I edited the index.html file to add Tom's content.

![tom-content](./images/edit-file.png)

- I checked the status to confirm the changes have not been staged.

![git-status](./images/git-status3.png)

- I added the changes to the staging area.

![git-add2](./images/git-add.png)

- I checked the status again to confirm the changes have been staged.

![git-status4](./images/git-status4.png)

- I committed the changes with a message.

![git-commit2](./images/git-commit2.png)

- I pushed the Tom's branch to GitHub.

![git-push2](./images/git-push-tom.png)

### Jerry's work

- I switched back to the main branch.

![git-checkout-main](./images/git-checkout-main.png)

- I pulled the latest changes from the remote repository to ensure I have the latest version of the main branch.

![git-pull](./images/git-pull-update.png)

- I created a new branch for Jerry's work.

![git-branch-jerry](./images/git-switch-jerry.png)

- I staged Jerry's changes to the index.html file and commited them with a message.

![git-commit-jerry](./images/git-add-commit-jerry.png)

- I pushed Jerry's branch to GitHub.

![git-push-jerry](./images/git-push-jerry.png)
