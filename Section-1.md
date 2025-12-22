# Section - 1
# Level - 1 - Git Commit

This level introduces the concept of Git commits.

I performed commits on the main branch to understand how Git saves changes.

Each commit represents a saved state of the repository.

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

I created two commits on the main branch.

I understood that each commit stores a snapshot of the repository.

I observed that the main branch pointer moves forward after every commit.

I learned that HEAD points to the current branch.

# Level - 2 - Branching in Git

This level explains how to create a new branch and switch between branches.

I created a branch named bugFix and moved HEAD to it without creating a new commit.

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

I created a new branch named bugFix.

I switched from main to bugFix.

I observed that no new commit was created.

I understood that HEAD now points to the bugFix branch.

# Level - 3 - Merging in git

This level demonstrates merging two branches.

I added commits to both bugFix and main branches and then merged bugFix into main.

Since both branches had different commits, Git created a merge commit.

<img width="1920" height="1003" alt="Screenshot 2025-12-22 151354" src="https://github.com/user-attachments/assets/0d22c419-c14e-46b3-9600-8bab14374cf9" />


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
git checkout main
git commit
```

<img width="1920" height="1005" alt="Screenshot 2025-12-22 151631" src="https://github.com/user-attachments/assets/01150e26-1563-4889-a7b7-fb96223293be" />

## Commands Used

```bash
git merge bugFix
```

# Outcome

I created and worked on a separate branch.

I added commits on both branches.

I merged bugFix into main.

I observed how Git creates a merge commit when histories diverge.


# Level - 4 - Rebase Introduction

This level explains the rebase operation in Git.

I created commits on both branches and rebased bugFix onto main.

Rebase moved the commits of bugFix on top of main, resulting in a linear history.

<img width="1920" height="1011" alt="Screenshot 2025-12-22 152616" src="https://github.com/user-attachments/assets/a7c865e9-5567-47c9-a1b7-2742802ba99d" />


## Commands Used

```bash
git branch bugFix
git commit
```

<img width="1920" height="1000" alt="Screenshot 2025-12-22 151929" src="https://github.com/user-attachments/assets/3d95cc5a-7d5d-43fb-910b-03f5d1a79c2d" />

## Commands Used

```bash
git checkout bugFix
git commit
```

<img width="1920" height="998" alt="Screenshot 2025-12-22 152647" src="https://github.com/user-attachments/assets/058ded55-6128-4a71-9446-882a44e57f03" />

## Commands Used

```bash
git checkout main
git commit
```

<img width="1920" height="1009" alt="Screenshot 2025-12-22 152731" src="https://github.com/user-attachments/assets/1b33e460-241b-4cac-b0fb-fefcfeef4271" />

## Commands Used

```bash
git checkout bugFix
git rebase main
```

# Outcome

I created commits on both branches.

I rebased the bugFix branch onto main.

I observed that no merge commit was created.

I understood how rebase helps maintain a clean commit history.
