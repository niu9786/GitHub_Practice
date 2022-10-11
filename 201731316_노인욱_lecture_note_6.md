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

