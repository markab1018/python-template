# SOMEPROJECT

<!--
After creating a repository off of this template make sure to clean up project name and paths. Also there are templates for both using Jenkins and GitHub Actions. Delete whichever is not in use. And delete this comment ;)
-->

SOMEPROJECT is set up to run in bash *NIX environments. If running on Windows many of the scripts will not work properly.

## Installing the Package
TODO

## Setting up Development Environment
In order to set up a development environment for this tool, first clone the GitHub repo. Then create a virtual environment and install the tool with testing dependencies. Finally set up your githooks to ensure code that doesn't pass the static and unit tests is not committed.

```
git clone TODO
cd TODO
python3 -m venv .venv
pip install -e .[test]
git config core.hooksPath .githooks
```
