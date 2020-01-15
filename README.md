# owutil cli
## Installation

#### > pip install owutil==0.1.5

Before you start using the command, you must go to the right project with the right credentials in your git config.

#### Commands
- merge command
  ex: owutil merge <branch> <version>
  - params:
    1. branch = name of the branch you want to merge to master (ex: release/0.1.2)
    2. version = choices are only (major, minor, patch)


1. Merge hotfix branches to master
  - owutil merge hotfix/0.1.2 patch

1. Merge release branches to master
  - owutil merge release/0.4.0 minor
