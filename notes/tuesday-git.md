# Working Directory vs Staging vs History
- Working Directory: the files you are currently editing on your machine. Changes here are not yet prepared for a commit.
- Staging: the area where you place selected changes that you want included in the next commit. You move changes here with git add.
- History: the record of commits already saved in Git. You view it with commands like git log.

# Branching Rules
These are team guidelines for how branches should be created and used. 
Common rules are:

- Keep main or master stable
- Create a new branch for each feature, bug fix, or task
- Use clear branch names such as feature/login-page or bugfix/payment-error
- Do not work directly on main
- Delete branches after merging if no longer needed

# Pull Request Expectations
A pull request is a request to merge your branch into another branch, usually *main* or *develop*.
