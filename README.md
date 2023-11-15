# test

Certainly! Here are the Git commands along with sample examples:

1. **git init:**
   - Initialize a new Git repository.
     ```bash
     git init
     ```

2. **git clone [repository_url]:**
   - Clone a repository into a new directory.
     ```bash
     git clone https://github.com/example/repo.git
     ```

3. **git add [file(s)]:**
   - Add changes in the working directory to the staging area.
     ```bash
     git add file.txt
     ```

4. **git commit -m "commit message":**
   - Record changes to the repository with a descriptive message.
     ```bash
     git commit -m "Add file.txt"
     ```

5. **git status:**
   - Show the status of changes as untracked, modified, or staged.
     ```bash
     git status
     ```

6. **git pull:**
   - Fetch changes from a remote repository and merge them into the current branch.
     ```bash
     git pull origin master
     ```

7. **git push:**
   - Push changes to a remote repository.
     ```bash
     git push origin master
     ```

8. **git branch:**
   - List all local branches.
     ```bash
     git branch
     ```

9. **git branch [branch_name]:**
   - Create a new branch.
     ```bash
     git branch new-feature
     ```

10. **git checkout [branch_name]:**
    - Switch to the specified branch.
      ```bash
      git checkout new-feature
      ```

11. **git merge [branch_name]:**
    - Merge the specified branch into the current branch.
      ```bash
      git merge new-feature
      ```

12. **git log:**
    - Show a log of all commits.
      ```bash
      git log
      ```

13. **git remote -v:**
    - Show the remote repositories configured for the current repository.
      ```bash
      git remote -v
      ```

14. **git fetch:**
    - Download objects and refs from another repository.
      ```bash
      git fetch origin
      ```

15. **git diff:**
    - Show changes between commits, commit and working tree, etc.
      ```bash
      git diff HEAD
      ```

16. **git stash:**
    - Temporarily save changes that are not ready to be committed.
      ```bash
      git stash
      ```

17. **git remote add [remote_name] [remote_url]:**
    - Add a remote repository.
      ```bash
      git remote add upstream https://github.com/upstream/repo.git
      ```

18. **git remote remove [remote_name]:**
    - Remove a remote repository.
      ```bash
      git remote remove upstream
      ```

19. **git log --graph --oneline --all:**
    - Display a summarized view of the commit history with branches.
      ```bash
      git log --graph --oneline --all
      ```

20. **git reset [commit] :**
    - Reset the current HEAD to the specified state.
      ```bash
      git reset --hard commit_sha
      ```

Feel free to use these examples as a starting point for your workshop materials. Adapt them to fit the specific context and content you plan to cover.
