# Section - 1
# Level - 1 - Git Commit

This level introduces Git commits.

Two commits are created on the main branch.

Each commit records the current state of the repository.

The main branch pointer advances with each commit, and HEAD remains on main.

<img width="1920" height="1005" alt="Screenshot 2025-12-22 150814" src="https://github.com/user-attachments/assets/343fae9a-e0ba-406e-860a-04524862c37e" />

## Commands Used
```bash
git commit
```
<img width="1920" height="994" alt="Screenshot 2025-12-22 150845" src="https://github.com/user-attachments/assets/3c40c81c-018a-4514-ba90-b6de5da32060" />



## Commands Used
```bash
git commit

```
# Outcome

Commits are created successfully

Branch pointer moves forward

Repository history is updated


# Level - 2 - Branching in Git

This level demonstrates branch creation and branch switching.

A new branch named bugFix is created using git branch.

The git checkout command moves HEAD to the bugFix branch.

No new commits are created in this level.

<img width="1920" height="1005" alt="Screenshot 2025-12-22 151130" src="https://github.com/user-attachments/assets/531258d1-6070-4b74-a38a-c5f5a85b9f44" />


## Commands Used

```bash
git branch bugFix
```

<img width="1920" height="1011" alt="Screenshot 2025-12-22 151220" src="https://github.com/user-attachments/assets/2a6c0806-c1f4-4641-83bf-c3b3b213228e" />

## Commands Used

```bash
git checkout bugFix
```

## Outcome

New branch is created

HEAD points to bugFix

# Level - 3 - Merging in git

This level demonstrates merging branches.

A new branch bugFix is created and a commit is added to it.

Another commit is added on the main branch.

The git merge command merges bugFix into main.

Since both branches contain different commits, Git creates a merge commit.


<img width="1920" height="1005" alt="Screenshot 2025-12-22 151444" src="https://github.com/user-attachments/assets/ab07a287-30a7-4572-8038-2e039ba259fb" />

## Commands Used

```bash
git branch bugFix
```

<img width="1920" height="1005" alt="Screenshot 2025-12-22 151444" src="https://github.com/user-attachments/assets/b9c7689b-27cc-4750-8268-be8b0adcb271" />

## Commands Used

```bash
git checkout bugFix

git commit
```

<img width="1920" height="1003" alt="Screenshot 2025-12-22 151531" src="https://github.com/user-attachments/assets/a7389978-7b68-49d9-b1a6-4a272d360074" />

## Commands Used

```bash
git commit
git checkout main
```
