# Linux: Filesystem Permissions & Access Control

## Project Description
Audited a research directory to ensure sensitive project files were only accessible to authorized users.

## Tasks Performed
- **Directory Analysis:** Used `ls -la` to view hidden files and current permission strings.
- **Enforcing Least Privilege:** - Identified `project_k.txt` had "world-writable" permissions (`-rw-rw-rw-`) and restricted them.
  - Used `chmod` to remove write access from "others" on sensitive hidden files.
- **Directory Hardening:** Modified permissions on the `drafts` directory to ensure only the owner could enter and modify the contents (`drwx------`).

## Commands Used
- `ls -la` (List all with permissions)
- `chmod` (Change mode)
- `chown` (Change owner)
