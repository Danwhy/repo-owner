# Repo-Owner
<br>

## Git/Github

Git is a version control system.  
Github is an online, git based hosting service.  
<br>

## Github Flow

### What it is
Github flow is made up of five steps
1. Create a branch  
 * Create a branch from the master with a name  that describes the feature being implemented.  
2. Add commits  
 * Each time a change is made, commit the change with a message describing what you've done.  
3. Open a pull request  
 * Open a pull request when you want to share your code with your other team members.  
4. Discuss and review  
 * Other team members can leave comments on your proposed changes  
5. Merge and deploy  
 * Once the code has been reviewed, it should be merged with the master branch. This code should be deployable, and deployed immediately.

### Benefits  
This is a simple, structured workflow that makes it easy to see every change that has been made, and easy to revert if any bugs occur.

### Other Workflows  
Centralized Workflow  
* Team members clone the master branch and work on features until they are complete. They then push these to the remote master branch. This workflow is efficient and simple, but requires much less code review, which could lead to issues with large teams.

Gitflow
* Similar to Github flow, but includes an intermediary **develop** branch that is used to polish and prepare features for deployment. This flow allows for well defined development phases, but does not deploy as often as Github flow.  

Forking Workflow  
* The workflow most commonly used for open source projects. Each person working on the project has their own fork, which they can branch and work on as they please. The project owner is the only person that can merge pull requests to the official codebase.
<br>

## Git Commands

### See the difference between your current files and your last commit
```git
git diff HEAD
```

### See the difference between your staged files and your last commit
```git
git diff --staged
```

###Push local commits to remote origin  
``` git
git push [origin] [branch to push to]
```

###Push and remember arguments
``` git
git push -u [origin] [branch to push to]
```
This will remember the parameters, so next time we push (or pull), we only need to type **git push** (or pull).
