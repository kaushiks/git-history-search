# git-history-search

Look for a specific pattern (Python3 regex syntax) in blobs reachable from all
revisions in a git repository.

## Usage
```
$ git-history-search
usage: git-history-search /path/to/git/repository regex
```

## Requirements
* Python 3
* [Pygit2](https://github.com/libgit2/pygit2)

## Installation
```
pip(3) install pygit2
cp ./git-history-search /usr/local/bin
```
