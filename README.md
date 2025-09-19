# Git Exercises Workshop

## 🔹 Exercise 1: Getting Started with Git

- Initialize a repository (`git init`).
- Create a README.md file with a brief description.
- Add and commit this file (`git add`, `git commit`).
- Check the repository status (`git status`, `git log`).

## 🔹 Exercise 2: History and Commits (30 min)

- Create operator file (operator.py)
- Update Readme file to document this file
- Make several commits while modifying them incrementally.
- Use `git log`, `git diff`, `git checkout` to explore the history.
- Perform a revert on a specific commit.

## 🔹 Exercise 3: Branches and Merges

- Create a branch called feature-X.
- Modify the project on this branch (add a function to operator.py).
- Return to main and make another change.
- Merge feature-X into main.
- Visualize the commit graph (`git log --oneline --graph --all`).

## 🔹 Exercise 4: Collaboration with Remote Repositories (40 min)

- Clone this repository
- Each student works on their personal branch
- Push the branch to the remote (`git push origin my-branch`)
- Create a pull request (or merge request)
- Retrieve others' modifications with `git pull`

## 🔹 Exercise 5: Conflicts & Advanced Workflows

- Intentionally create a conflict (two students modify the same line in a file)
- Resolve the conflict manually, then commit
- Introduce the GitFlow workflow (develop, feature, release, hotfix branches)
- Mini-simulation: create a feature and merge it into develop
