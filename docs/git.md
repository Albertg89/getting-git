# Git 

## Commands

- `git init`: Initiates a .git repo to "track" all changes within our project.
- `git add <argument>`: Moves file/files from untracked to staged.
- `git commit -m '<message>'`: Generates a seaved state with descriptive message
- `git remote -v`: Describes our remote connection to our github repo
- `git remote add origin <url>`: Connect the remote connection to github repo
- `git push origin <branch>`: Copy and past the current branch to github

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Branching
- `git checkout <commit-hash>`: To view a previous state of our project at the provided hash.
- `git checkout -B <commit-hash>`: Creates a cope of current branch and switches into the new copy.
- `git checkout <branch-name>`: Switches branches.
- `git branch`: Displays all existing and current branches.


## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
