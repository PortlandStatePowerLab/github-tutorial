# github-tutorial
Overview of PortlandStatePowerLab's repos organization and general guidelines for using GitHub.

## Repository Naming

The naming convention for repositories will be *kebab-case* where each word is seperated by a hyphen. In an attempt to group related projects we have adopted the following standard:

- <organization>-<technology>-<description>
  - doe-egot-me
  - cmake-tutorial *where the organization is PSU*

## README

The README.md file will act as a living document for the project to describe: background, design, setup, and operating instructions. The objective is to provide all the resouces neccessary for someone to pickup the project on their own. The following link provides and overview of the markdown syntax and usage.

- https://guides.github.com/features/mastering-markdown/

## LICENSE

If a project uses external resources it should have a LICENSE file that describes which licenses are included within the project. 

## .gitignore

A gitignore file should be include with all repositories to reduce clutter. Use the template .gitignore files for the specific language used as a starting point and make modifications when necessary to remove files/folders as needed. The following link shows example patterns for matching files and folders:

- https://git-scm.com/docs/gitignore

## Workflow

Finally we get to using github for revision control. If you are unfamiliar with using github I recommend reading the [Git Handbook](https://guides.github.com/introduction/git-handbook/). You can use git from the command line or git gui or from an extension for your favorite IDE or editor. We will discuss that more in our development-tutorial. The GitHub flow can be summerized in six steps:

- **Create a branch:** these typically represent a feature or topic that is going to extend the main branch functionality.
- **Add commits:** stage modified changes, comment on what was done, and push to remote branch.
- **Open a pull request:** notify other developers that your feature or topic is complete and ready to be integrated into the main branch.
- **Discuss and review code:** other developers validate changes, run unit tests, and compare modified files.
- **Merge:** combine the main branch with the feature branch to adopt the feature or topic.
- **Deploy:** The repository goals are complete and all features have been developed and merged.

