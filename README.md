# Misc

The purpose of this repository is simply to keep notes about methodologies that I have created or that I have found to work well for me in particular. Likewise, I will also keep configuration files that I use in my projects.

## Table of contents

- [Git](#git)
  - [Formatting commit messages](#formatting-commit-messages)
- [Files](./files)
  - [Styles](./files/styles/)
  - [Lint and formatting](./files/lint-and-formatting/)

## Git

### Formatting commit messages

Both pull requests and individual commits follow the `git-flow` format (`(feature | chore | fix): <message>`).

**Frequent flags (commits and PR)**:

- `feature`: Any addition of functionality not previously present in the project.

- `chore`: Routine maintenance tasks or those related to tests, configuration files, etc.

- `fix`: Bug fixes.

**Additional flags (commits)**:

- `add`: The only purpose of the commit or pull request was to add a file.

- `rm`: The only purpose of the commit or pull request was to remove a file.

- `hotfix:` A change commited directly to the branch which deploys the project with the purpose of fixing a bug (not encouraged).

- `rp`: Replace a static file with another with the same name. Let's think about a static asset called `image.png`, if we delete it and paste another with the same name we should use this flag.

- `update`: I commonly use this flag when I update the content of a plain text file like a README or a markdown post.
