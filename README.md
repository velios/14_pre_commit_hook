# Quadratic Equations Solver

This repository contains Git hook file `pre-commit` which using standard features of git to checks the code with patterns defined in the file

### How to use

##### Install
```bash
$ chmod +x pre-commit # make pre-commit executable
$ cp pre-commit .git/hooks/pre-commit # cope file pre-commit to git default directory
```
Sample `pre-commit` check all tests in `tests.py` is passed. If all ok, you can make commit. If not scripts print warning message and cancelled commit.

##### Sample use
```bash
$ git commit
Tests fail. Commit is not possible
```
Special mistake made in `quadratic_equation.py`, fix this file to all tests pass.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
