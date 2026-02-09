# git-commands
One place solution for all git commands


This section explains how to create and switch branches in Git using common commands.

🔹 Create a New Branch and Switch to It Immediately

Creates a new branch from a specified source branch and switches to it.

git checkout -b <new-branch-name> <source-branch-name>


Example (from main):

git checkout -b feature-login main

🔹 Create a New Branch When Already on the Source Branch

Creates a new branch from the current branch and switches to it.

git checkout -b <new-branch-name>

🔹 Create a New Branch Without Switching

Creates a new branch but keeps you on the current branch.

git branch <new-branch-name> <source-branch-name>


Example:

git branch feature-login main

🔹 Create a New Branch Without Switching (Already on Source Branch)

Creates a new branch from the current branch without switching.

git branch <new-branch-name>

🔹 Switch to an Existing Branch

Switches from the current branch to an existing branch.

git checkout <existing-branch-name>


Example:

git checkout feature-login