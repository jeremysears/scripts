# Handy utilities and dotfiles

For easy installation, use [rcm](https://github.com/thoughtbot/rcm), which you
can install with the following command:

```
brew tap thoughtbot/formulae
brew install rcm
```

You can then symlink the utilities in this repo to your ~/bin directory by
executing the following command:

```
$ RCRC="$(pwd)/.rcrc" rcup -v
```

Remove the symlinks using:

```
$ RCRC="$(pwd)/.rcrc" rcdn -v
```

Happy CLI'ing.
