# Git Flow Prototype #

**Note**: Please merge your own pull requests, there's no need to assign them to someone.

You can use this repository to learn the commands needed for Git Flow. The main idea is to branch off the `develop` branch rather than the `master` branch. When you make pull requests, you want to merge into `develop`, not `master`.

## Exercise ##
1. Clone the repository.
2. Checkout a new feature branch called `feature/my-name`.
3. Add your name to the file `names.txt` and commit the changes on the `feature/my-name` branch.
4. Push your feature branch and then submit a pull request to merge your feature branch into `develop`. (Make sure to delete the branch on GitHub)
5. Delete your local feature once the pull request is merged.
6. Sync your local `develop` branch with the remote.

***

## Solution ##
1. `git clone https://github.com/kmckenna-cognito/git-flow-prototype.git && cd git-flow-prototype`
2. `git checkout -b my-name develop`
3. `git commit -a -m "Added my name"`
4. `git push -u origin feature/my-name`
5. `git checkout develop && git branch -d git-flow-prototype`
6. `git pull`
