# git-recipes
Shortcuts for git:
* Remove all local branches except pattern

    `git branch | grep -v "master\|develop\|$(git branch --show-current)" | xargs git branch -D
