# Cheatsheet

## Git:

### Resources

* [Atlassian tutorials](https://www.atlassian.com/git/tutorials)

### Style Guide

    type: subject (required)
      Ex: feat: Added cool feature

    body (optional)
      Ex: A more detailed description.

    footer (optional)
      Ex: Resolves: #123
          See also: #456, #789

#### Types

* **feat**: a new feature
* **fix**: a bug fix
* **docs**: changes to documentation
* **style**: formatting, missing semi colons, etc; no code change
refactor: refactoring production code
* **test**: adding tests, refactoring test; no production code change
* **chore**: updating build tasks, package manager configs, etc; no production code change

### Commands

**rename file:**
    git mv app.js App.js

**Adding a remote**
    git remote add $REPO_URL

**Verify remote**
    git remote -v
