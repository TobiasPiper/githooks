# Githooks

[Git hook documentation](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)

## Installation

Clone this repository to ~/.githooks for global or to your projects .git/hooks folder for local / project based use 

## Commit

* commit-msg: Enforces the commit message to match the pattern of `[JIRA-4711] Your message`
* pre-commit: Prevents commits on master and develop branch

## Push

* pre-push: Checking for gradle or maven project layout and running tests; Preventing push if there are untracked files

## Great addition, for reference
* https://github.com/mnagel/clustergit
