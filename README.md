# doc-git-hooks
Git hooks for processing documentation files

## Installation
To use these hooks in your GitHub repository, clone this repository and make a symbolic link from the specific hook file to the `.git/hooks` subdirectory of your documentation repository. For example:

```
# '~/devel/' is your GH checkouts dir, ok?
$ git clone git@github.com:openSUSE/doc-git-hooks.git ~/devel/doc-git-hooks

# this is your doc repo
$ cd ~/doc/ses/.git/hook/

# creates 'pre-commit' in '~/doc/ses/.git/hook/'
$ ln -s ~/devel/doc-git-hooks/pre-commit pre-commit
```
That is it

Have fun :-)
