# IT-Hub-Solarboat
Parent Repository for all code related to the IT-Hub's Solarboat project.

## How to use:
Code must not be commited to this repository directly. Instead, code will be commited to seperate repositories before being added as sub-modules to the parent repository.

### Using submodules:
To add a sub-module to the repository, you must do the following:
1. Clone this repository.
2. run ```git submodule add <repository path(the one you use when cloning repo via url)> <filepath within this repo. Must follow the convention 1_word_summary_of_repo_purpose/src>```
3. Commit the change to the repository. It should automatically run update_submodules.yml.
Updates to this repository happen at 0.00 UST, but a manual update can be forced by going into actions and running 'update_submodules.yml
