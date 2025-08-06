It looks like there was an error saving the Markdown file. Let me try again for you.

There seems to be a temporary issue saving the file on the system.


```markdown
# 🚀 Git Basic Commands

## 🛠️ Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## Starting a Git Project

```bash
git init                      # Initialize a new Git repo
git clone <repo_url>         # Clone an existing repository
```

## File Handling

```bash
git add <file>               # Stage a file
git add .                    # Stage all changes
git status                   # Show status of files
git rm <file>                # Remove file from repo
```

## Committing Changes

```bash
git commit -m "Your message"       # Commit staged changes
git commit -am "Your message"      # Add & commit tracked files in one step
```

## Branching

```bash
git branch                   # List branches
git branch <branch-name>     # Create new branch
git checkout <branch-name>   # Switch to a branch
git checkout -b <new-branch> # Create and switch
```

## Merging & Rebasing

```bash
git merge <branch>          # Merge into current branch
git rebase <branch>         # Reapply commits on top of another base
```

##  Sync with Remote

```bash
git remote -v               # Show remote repo
git fetch                   # Get updates from remote
git pull                    # Get and merge remote changes
git push                    # Push local commits to remote
git push -u origin <branch> # Push and set upstream
```

##  History

```bash
git log                     # Show commit history
git log --oneline           # Condensed log
```

##  Undo & Reset

```bash
git reset <file>            # Unstage file
git checkout -- <file>      # Discard changes in file
git revert <commit>         # Undo commit (safe)
git reset --hard <commit>   # Reset to previous commit (destructive)
```
```
