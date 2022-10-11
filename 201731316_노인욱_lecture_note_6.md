# Lecture Note 1
### about GIT

## Version Control
---
For software development and other documentation works, version control system is necessary.

### Basic solution: make copies
i.g. project_final.txt -> project_final_modif1.txt -> project_final_modif2.txt ...

### Changes vs Snapshots
- Changes: Any subsequent versons are recorded as a changes from the root.
- Snapshots: each version is stored in its entirely.

### Version Control System
1. Local VCS: Operated only in local. It is vulnerable when coworking with other developers.
2. Centralized VCS: Move the files and changing history to a server. Each clients contact to the server and take a specific version.
3. Distributed VCS: All the clients take a backup of the server. DVCS is good at server errors or offline works.

### Three states in GIT
- Modified(Working DIrectory): Checkout specific version at GIT Directory. User do their project works at here.
- Staged(Staging Area): The content worked on the working directory swing by here.
- Committed(GIT Directory): All the metadata and object dbs of the project are saved in here.

### GIT Configuration
GIT configurations are stored in three levels
1. System: All the repositories and users of the computer
2. Global: All the repositories of current user
3. Local: Specific repository

#### To use
```sh
$ git config --<range> <name> <values>
```

### Initializing repository
create and initialize a repository in an existing directory
```sh
$ git init
```

### Checking repository status
Check the status of working directory and staging area
```sh
$ git status
```

### Adding a new file to be staged
To stage fixes the content of working directory
```sh
$ git add [file name/directory]
```

To stage fixes all the contents of current directory
```sh
$ git add .
```

Unstaging a file
```sh
$ git rm -cached [file name]
```

Ignoring a file
```sh
$ nano .gitignore
```

To commit
```sh
$ git comit -m "commit message"
```

To change branch name
```sh
$ git branch -m [current] [to change]
```
