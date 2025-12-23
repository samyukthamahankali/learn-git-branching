# Section 3

# Level - 1 - Cherry-pick Intro

This level introduces the cherry-pick command in Git.

Cherry-pick is used to copy specific commits from one branch and apply them onto the current branch.

Only the selected commits are applied, without merging the entire branch.

# Goal to reach 

<img width="1920" height="980" alt="3 1" src="https://github.com/user-attachments/assets/36f37f31-af79-4909-9950-fe338c11ba6b" />

<img width="1920" height="1000" alt="3 1 1" src="https://github.com/user-attachments/assets/6b35e9bf-026f-4e0b-ae66-08af79f04d08" />

## Commands Used
```bash
git cherry-pick C3 C4 C7
```

Specific commits are copied onto the current branch.

Commit history is updated with selected changes only.

The purpose of cherry-pick is understood.

Unnecessary commits from other branches are avoided.


# Level - 2 - Interactive Rebase Intro

This level introduces interactive rebase in Git.

Interactive rebase allows editing, reordering, or removing commits before applying them.

The rebase target can be specified using a branch name or a relative reference.

# Goal to reach 

<img width="1920" height="1005" alt="3 2" src="https://github.com/user-attachments/assets/636c246e-df88-4721-bb4e-4f55bb878d35" />

<img width="1920" height="1013" alt="3 2 1" src="https://github.com/user-attachments/assets/0fd0ea70-564c-4a3b-bd72-17dfa7bae445" />

## Commands Used
```bash
git rebase -i overHere
```
Interactive rebase is executed successfully.

Commits are reorganized during the rebase process.

Commit history becomes cleaner and more structured.

The flexibility of interactive rebase is understood.
