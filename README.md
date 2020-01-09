# git-recipes
Shortcuts for git:
* Remove all local branches except pattern

    `git branch | grep -v @regexp | xargs git branch -D` e.g @regexp = "master\|develop"
