# cheatsheet
A collection of tips and tricks for developpers.

## Git
For a satisfying list of Github-flavored Mardown commands, visit [this link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Pull a specific branch
When cloning or pulling a code, you may want to get a specific version of it. This is generally called a branch. This is how you do it (inspired from [this thread](https://precice.discourse.group/t/installation-of-precice-v2-and-its-openfoam-adapter/171/7)):

```
git clone --single-branch --branch OpenFOAM6 https://github.com/precice/openfoam-adapter.git
```
