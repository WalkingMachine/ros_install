# ros_install
Repo that contains all of the rosinstall file


## Add packages

To add a packages to the rosinstall just add your packages to the following files: [desktop.rosinstall](desktop.rosinstall) and [sara.rosinstall](sara.rosinstall)

Example:
```
- git:
    local-name: example_packages
    uri: https://github.com/WalkingMachine/example_packages.git
```

## Pull Request
One pull request for adding or removing a packages. This is to be able to open a discussion about why to add or remove that packages
