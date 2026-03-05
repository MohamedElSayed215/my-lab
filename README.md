# Git Lab 1 🚀
**Author: Mohamed ElSayed**

## Commands Used in This Lab

### Setup
| Command | What it does |
|---------|--------------|
| `ssh-keygen -t ed25519 -C "email"` | Generate SSH key |
| `ssh -T git@github.com` | Test SSH connection |
| `git config user.name "name"` | Set username |
| `git config user.email "email"` | Set email |

### Create & Connect
| Command | What it does |
|---------|--------------|
| `git init` | Create new local repo |
| `git remote add origin URL` | Connect to GitHub repo |
| `git remote -v` | Check remote connection |

### Daily Work
| Command | What it does |
|---------|--------------|
| `git status` | Check what changed |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Save a snapshot |
| `git log --oneline` | View commit history |

### Push & Pull
| Command | What it does |
|---------|--------------|
| `git push origin master` | Upload to GitHub |
| `git push -f origin master` | Force push to GitHub |

### Undo
| Command | What it does |
|---------|--------------|
| `git reset --hard HEAD~2` | Delete last 2 commits ⚠️ |
| `git reset --hard <id>` | Go back to specific commit ⚠️ |
| `git commit --amend -m "msg"` | Edit last commit |
| `git revert HEAD~2..HEAD` | Safely undo commits ✅ |
