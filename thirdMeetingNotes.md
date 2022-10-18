# Git merges, Review of project progress, and the next few days

## Git merge

We went over a couple notes of what to do when merging branches. Always try to do this in a group, and in a meeting so everyone can have the most update main branch

NOTE: We should only merge ONE BRANCH AT A TIME

- Make sure the branch you are working on is up to date. You can use git status by checking if it is or not. If it isn't add, commit and push your changes.
- Once that is gone checkout to the main branch by using `git checkout main`
- Pull the most recent commits from the branch by using `git pull`. You'll probably have to create a commit message before moving on.
- Run git status one more time and make sure you don't have anything to commit or push. If you have pulled a teammates commit, you'll also have to push the changes.
- Once this is done you should have the most recent main branch, in the event that you have commit conflicts, review the code with your teammates and make sure you are accepting the right changes. Either incoming, or current.
- Once everything is in the clear and you have the most recent branch changes, you can beging merging your branch to the main
- Run `git merge` following the name of your branch (e.g. `git merge features/login`)
- You should see all your work and new files pop up. You can again commit those changes and push them to the main branch
- Once you've done that, your teammates can grab your changes by running `git pull` in the main branch

## Project progress

We went over how the project is coming along. 
The basic CSS is working great at this time.
API has been implemented.
Routes are working great.

## Next steps

Creating a view map page and edit map page
We went over how the edit map page should not have the map displayed. Instead, it should be a bunch of input boxes with prefilled information pulled from all the points of a certain map.