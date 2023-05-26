# Git and Github

## GIT - Definition

- Git is a distributed version control system designed to track changes in files and coordinate work among multiple developers.
- It allows developers to work on a project simultaneously, maintain a history of changes, and easily collaborate on code.
- Git operates locally, enabling users to work offline and commit changes to their local repository.

**GIT key concepts:**

-  As GIT tracks all the changes you make at the code, you can easily search all the changes made and quickly locate the problem. 
-  GIT let you go back to a previous version of your code with a single command.
-  87% of developers and companies use this control system, so for finding a job it's important to know it.
-  Key concepts to start:

    1. Repository: A repository (or repo) is a collection of files and folders that are being tracked by Git. It contains the complete history and branches of a project.
    2. Commit: A commit represents a snapshot of changes made to the repository. It contains a unique identifier, a commit message, and references to the changes made.
    3. Branch: A branch is a separate line of development within a repository. It allows for parallel work and independent experimentation without affecting the main codebase.
    4. Merge: Merging combines changes from different branches into a single branch, typically the main branch, to incorporate new features or bug fixes.
    5. Pull: Pulling refers to fetching changes from a remote repository and integrating them into the local repository.


### Once GIT and github it's installed you run it by running commands in your local terminal

    ***GIT common comands***:
**Key Git Commands:**

```sh
`git init` #Initializes a new Git repository in the current directory.
`git clone [repository URL]` #Copies an existing repository from a remote source to the local machine.
`git add [file(s)]` #Adds file(s) to the staging area, preparing them for a commit.
`git commit -m "[commit message]"` #Creates a new commit with the changes staged in the repository.
`git push` #Pushes the committed changes to a remote repository.
`git pull` #Fetches changes from a remote repository and merges them into the current branch.
`git branch` #Lists all branches in the repository.
`git checkout [branch]` #Switches to the specified branch.
`git merge [branch]` #Merges the specified branch into the current branch. 
``` 
    

## GITHUB - Definition

- GitHub is a web-based hosting service for Git repositories, providing additional features for collaboration, code review, and project management.
- It allows multiple developers to work together on the same project, managing code, issues, and pull requests.


**GitHub Key Concepts:**

1. Repository Hosting: GitHub hosts Git repositories, providing a central location for collaboration and code sharing.
2. Pull Requests: Pull requests allow developers to propose changes to a repository and request a review before merging them.
3. Issues: Issues are used to track and discuss tasks, enhancements, bugs, or other topics related to a repository.
4. Fork: Forking a repository creates a personal copy of the original repository, allowing you to freely experiment with changes.
5. Stars: Stars represent a way to bookmark repositories for future reference or to show appreciation for a project.


## Difference between git merge, git rebase and git squash.

1. **`git rebase`**: git rebase is used to integrate changes from one branch onto another by moving or combining commits.
    -It allows you to apply the commits of one branch onto the tip of another branch, resulting in a linear commit history.
    -It is commonly used to keep feature branches up to date with changes made in the main branch before merging.
    -This command can be helpful in creating a clean, linear history but should be used with caution when working in a team and sharing branches, as it rewrites commit history.


2. **`git merge`**: git merge combines changes from different branches into a single branch, typically the current branch or the branch being merged into.
    -It creates a new commit that represents the combination of changes from the merged branches.
    -Merging preserves the commit history of both branches, resulting in a more complex commit history compared to rebasing.
    -This command is commonly used to integrate feature branches into the main branch or combine changes from multiple branches.

3. **`git squash`**: git squash is not a built-in Git command, but rather a technique used to combine multiple commits into a single, cleaner commit.
    -It is typically used when you have several small, incremental commits that you want to consolidate into a larger, cohesive commit.
    -Squashing commits can make the commit history more concise and easier to understand for others reviewing the code.
    -It involves using interactive rebase (git rebase -i) to squash the selected commits into one, effectively rewriting the commit history.
