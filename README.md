## Lab 6

### Changes vs Snapshots
| Changes | Snapshots|
| ----- | ----- |
| Save the changed part |  Save the whole part  |

### Version Control
Essential for:
- Software development
- Document management
---
### Local Version Control
Tracks changes on a Local Computer.

### Centralized Version Control
Uses a Central VCS Server for version history.

### Distributed Version Control
Every contributor has a whole copy of the project.

---
### Three States in Git
1. **Modified**: File has been edited.
2. **Staged**: File is ready to be committed.
3. **Committed**: File changes are stored.

---
### Git Config

1. System Level: Affects all uses and repositories on the system.
2. Global Level: Affects all repositories of a current user.
3. Local Level: Specific to the current repository.

---
### ***How to***

- *Initialize a repository in an existing direcotry:*
```sh
$ git init
```
- *Check repository status:*
```sh
$ git status
```
- *Add a new file to be staged:*
```sh
$ git add [file_name]
```
- *Add all files to be staged:*
```sh
$ git add.
```
- *Unstage a file:*
```sh
$ git rm --cached [file_name]
```
---
- *Ignore a file:*
```sh
$ nano .gitignore
```
- *Commit:*
```sh
$ git commit -m "commit message"
```
- *See the records:*
```sh
$ git log
```
- *Change branch name:*
```sh
$ git branch -m master main
```
