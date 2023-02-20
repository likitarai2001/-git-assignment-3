# Git-Assignment 3

### Problem Definition

- Create a branch from the master and made some changes 

- Commit code in a branch.

- Revert recently committed code

### Steps

- Created repository named `git-assignment-3`
- Cloned the repository
![clone repo](images/Screenshot%20from%202023-02-16%2016-33-52.png)
- Renamed branch `main` to `master` using `git branch -M master`
- Added `README.md` file and pushed the code
![first commit](images/Screenshot%20from%202023-02-16%2016-37-06.png)
- Created branch `likita` and added `revert.md` file to it
![revert.md](images/Screenshot%20from%202023-02-17%2016-12-56.png)
- Check commit history for both `likita` and `master` branches
![commit history](images/Screenshot%20from%202023-02-20%2010-18-35.png)
- Revert recently commited code by using `git revert <commit_id>`
![revert commit](images/Screenshot%20from%202023-02-20%2010-31-56.png)


