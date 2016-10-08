# Welcome to the Repo!
This repository is an overview of the Introduction to GitHub course offered on Saturday, October 8th, at 10:30a.

## GitHub Flow
[GitHub Flow](https://guides.github.com/introduction/flow/)
The GitHub Flow is a branch-centric development workflow that prioritizes creating branches off the `master` or release branch. Changes to the project are applied to the `master` branch and deployed immediately. Although other workflows exist, such as the Git Flow, GitHub prefers this workflow as it doesn't focus on specific release versions but emphasizes building early and often.

### Issues
In some instances, before a branch is created to develop a change, an `Issue` is created to discuss an idea or issue for the current release of the project. Teams can discuss the expected next steps before individual collaborators begin working on the change.

### Branch
When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the master branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.

### Commits
Whenever you add, edit, or delete a file, you're making a commit, and adding them to your branch. This process of adding commits keeps track of your progress as you work on a feature branch.

Commits also create a transparent history of your work that others can follow to understand what you've done and why. Each commit has an associated commit message, which is a description explaining why a particular change was made. Furthermore, each commit is considered a separate unit of change. This lets you roll back changes if a bug is found, or if you decide to head in a different direction.

### Pull Requests 
Pull Requests initiate discussion about your commits. Because they're tightly integrated with the underlying Git repository, anyone can see exactly what changes would be merged if they accept your request.

You can open a Pull Request at any point during the development process: when you have little or no code but want to share some screenshots or general ideas, when you're stuck and need help or advice, or when you're ready for someone to review your work. By using GitHub's @mention system in your Pull Request message, you can ask for feedback from specific people or teams, whether they're down the hall or ten time zones away.

### Merge
Now that your changes have been verified in production, it is time to merge your code into the master branch.

Once merged, Pull Requests preserve a record of the historical changes to your code. Because they're searchable, they let anyone go back in time to understand why and how a decision was made.
