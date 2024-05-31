# IT-Hub-Solarboat
Parent Repository for all code related to the IT-Hub's Solarboat project.

## How to use:
Code should not be commited to this repository directly. Instead, code will be commited to seperate repositories before being added as sub-modules to the parent repository.

### Using submodules:
To add a sub-module to the repository, you must do the following:
1. Open .gitmodules
2. Add a new submodule, give it a relevant name.
3. Add a path for the submodule. The path will reflect where the code will be stored in this repository.
4. Add a url for the submodule. The url is the same url you use for cloning a repository to your desktop.
5. Commit the updated .gitmodules to the repository. It should automatically add your repository.
Updates to the sub-modules will be pulled daily, at midnight. If however, a change must be added immediately, you may navigate to the workflows, and run the 'update submodules' workflow.
