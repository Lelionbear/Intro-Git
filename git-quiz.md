# Beginner: Check for understanding

1. (multiple answer) Git is:
    - a. A version control system
    - b. Centralized
    - c. Distributed
    - d. The same as GitHub

2. (T/F) Git and GitHub are the same thing.

3. (multiple choice) What is GitHub?
    - a. A host for Git repositories
    - b. An integrated development environment (IDE)
    - c. The company that owns Git
    - d. All of the above

4. (fill in the blank) What is the name of the branch where the deployment-ready code is kept?

5. (T/F) Pull requests should be fully functional and not contain any bugs before getting teammates to look through them.

6. (T/F) Git stores the history of changes made to the codebase over time, and information about who made those changes.

7. (multiple choice) What is Markdown?
    - a. A syntax for easily formatting text on the web.
    - b. A way to grade projects on GitHub.
    - c. A programming language for creating web-based applications.
    - d. A way to deploy code to the cloud.

8. (multiple choice) What is a commit?
    - a. A snapshot of all the files in the repository.
    - b. A snapshot of just the changes from one time to the other.
    - c. A collection of branches.
    - d. Another name for a repository.

9. (multiple choice) What is a branch?
    - a. A pointer to a specific commit.
    - b. A link between the local and remote histories. 
    - c. The centralized location where repositories are stored.
    - d. A version of a file at a specific time.

10. (multiple choice) Which of the following commands will create a new branch?
    - a. `git checkout new-branch`
    - b. `git checkout -b new-branch`
    - c. `git clone new-branch`
    - d. `git create-branch new-branch`

---

# Intermediate: Check for understanding

1. (T/F) Staging, or `git add`, is required before creating a commit.

2. (multiple choice) Which of the following commands will allow you to change branches?
    - a. `git checkout`
    - b. `git clone`
    - c. `git add`
    - d. `git commit`

3. (multiple answer) What are the characteristics of a good commit message?
    - a. Short, less than 50 characters.
    - b. Describe the change introduced by the commit.
    - c. Tell the story of how your project has evolved. 
    - d. Commit messages are optional.

4. (T/F) The command `git push` is used to grab changes from the remote repository into your local repository.

5. (multiple choice) Which of the following commands will allow you to grab commits from the remote repository into your local repository? 
    - a. `git pull`
    - b. `git push`
    - c. `git checkout`
    - d. `git add`

6. (T/F) Merging allows you to combine changes made on one branch with the changes on a different branch.

7. (multiple choice) Which of the following commands will merge `branch-a` _into_ the `master` branch?
    - a. `git checkout master` and `git merge branch-a`
    - b. `git checkout branch-a` and `git merge master`
    - c. `git merge master` and `git checkout branch-a`
    - d. `git merge branch-a` and `git checkout master`

8. (T/F) Git can be used with most text editors.

9. (T/F) Cloning a repository gets you a local copy of only the `master` branch.

10. (multiple choice) What does the command `git branch` (without any options) do?
    - a. Shows you a list of your local branches.
    - b. Creates a new branch
    - c. Deletes a branch
    - d. Renames a branch

---

# Advanced: Check for understanding

1. (multiple choice) A command to see a repository's history is:
    - a. `git log`
    - b. `git commit`
    - c. `git clone`
    - d. `git push`

2. (multiple answer) What are some merge strategies you can use with Git?
    - a. Fast forward
    - b. Recursive
    - c. Extrapolated
    - d. Interdependent

3. (T/F) A rebase can be used to create a fast forward merge.

4. (multiple answer) What are the different options or `git reset`?
    - a. Soft
    - b. Mixed
    - c. Hard
    - d. Skip

5. (multiple choice) Which type of reset could you use if you'd like to keep changes in your staging area?
    - a. `git reset --soft`
    - b. `git reset --mixed`
    - c. `git reset --hard`
    - d. `git reset --skip`

6. (multiple choice) Which type of reset could you use if you'd like to keep changes in your working area?
    - a. `git reset --soft`
    - b. `git reset --mixed`
    - c. `git reset --hard`
    - d. `git reset --skip`

7. (multiple choice) Which type of reset could you use if you'd like to get rid of all your changes?
    - a. `git reset --soft`
    - b. `git reset --mixed`
    - c. `git reset --hard`
    - d. `git reset --skip`

8. (T/F) Git commits are dependent on its parent commit.

9. (T/F) Git revert is a dangerous command that alters the repository's history.

10. (multiple choice) Which of the following commands could alter a repository's existing history, therefore making it dangerous?
    - a. `git rebase`
    - b. `git commit`
    - c. `git revert`
    - d. `git branch`
