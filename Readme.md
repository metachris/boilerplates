# Boilerplate Collection

Boilerplates are basic setups with best practices. Just take the parts you like.

### Python

* [Python Script](https://github.com/metachris/boilerplates/tree/master/python)
* [Tornado Website](https://github.com/metachris/tornado-boilerplate)
* [App Engine Website](https://github.com/metachris/appengine-boilerplate)


### PEP8 Pre Commit Hook for Git

This [git pre-commit hook](https://github.com/metachris/boilerplates/tree/master/python/pep8-git-pre-commit-hook) checks for pep8 compatibility on committing, and aborts the commit if errors are found. Can be skipped by applying the `--no-verify` flag to `git commit`. This requires the tool `pep8` which can be installed via package managers and homebrew.

To use the commit hook in all projects on this system, copy it into the global git hook-templates directory (eg. `/usr/share/git-core/templates/hooks/`) as a file called `pre-commit` and set the permissions to executable. Afterwards you can enable this hook in existing repositories by calling `git init`. New repositories will use it by default.


### Dotfiles

[Boilerplate dotfiles](https://github.com/metachris/boilerplates/tree/master/dotfiles) is a collection of command line goodness for OSX and Linux. Includes `.bash_profile`, `.aliases`, `.exports`, and others.

