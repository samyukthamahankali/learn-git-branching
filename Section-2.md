# Section - 2

# Level - 1 -  Detach yo' HEAD

This level introduces the detached HEAD state.

The checkout command is used with a commit reference instead of a branch name.

HEAD points directly to the specified commit and is no longer attached to any branch.

# Goal to reach


<img width="1920" height="1000" alt="2 1" src="https://github.com/user-attachments/assets/372ceed7-bf44-457b-88d3-0f2127287dc4" />


<img width="1920" height="1009" alt="2 1 1" src="https://github.com/user-attachments/assets/4b105ef6-f0c5-443b-822f-6e395fe40939" />

# Commands used

```bash
git checkout C4
```

HEAD is detached from all branches.

The repository is checked out at a specific commit.

Branch pointers remain unchanged.

Detached HEAD behavior is understood.

# Level - 2 - Relative Refs

This level demonstrates relative references using the caret (^) operator.

The caret operator refers to the parent commit of a given reference.

The checkout command moves HEAD to the parent of the bugFix branch.

# Goal to reach

<img width="1920" height="1005" alt="k2 2" src="https://github.com/user-attachments/assets/68adaa51-e7b4-4f65-b53b-243dbec94a95" />


<img width="1920" height="1000" alt="2 2" src="https://github.com/user-attachments/assets/a88ef522-8149-4e80-84c3-d4e1bc7fc4ea" />

# Commands used

```bash
git checkout bugFix^
```
Relative commit references are used successfully.

HEAD moves to the parent commit of a branch.

Navigation through commit history is understood


