# Useful Git Commands

## Learning git and Github with Alpha

### Useful Comands

- git clone file-name
- git status
- git add file-name
- git commit -m "meaningful message here"
- git push origin main

### Vocabulary

- repository (repo) - a named folder on GitHub
- git - version control software
- GitHub - online platform for git, GUI for sharing code and collaboration
- local - your personal computer
- commit - adding a tracking number and message to your version
- diff - difference between GitHub and local
- markdown (.md)

### Processes

- changes in VSCode
- save in VSCode
- git add file-name
- git status
- git commit -m "what was changed"
- git push origin main
- refresh GitHub site

### Notes about Branching

- Branching protects your code from erros that can cause yoru app to be down in production
- Branching allows multiple people to work on code at the same time
- Branching is a best practice for all developers on all projects
- The main branch is the source of truth and should only ever have working code

### Branching Vocabulary

- branch - an alternative timeline where a developer can code safely
- main - the branch that is the source of truth, only working code allowed
- checkout - command to navigate between branches
- checkout -b - creates a new branch that doesn't currently exist
- deleting a branch - has to be deleted on local and on GitHub

### Branching Commands

- $ `git checkout -b branch-name` - creates branch that doesn't exist
- $ `git branch` - lists all of the current branches on your local
- $ `git branch -d branch-name` deletes a branch when you are done
- $ `git checkout main` - navigates back to the main branch