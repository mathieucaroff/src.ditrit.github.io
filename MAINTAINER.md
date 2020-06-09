# Maintainers of ditrit.io

## `git subtree`

The Syna module was originally added using the following command:

```shell
git subtree add --prefix=themes/syna https://github.com/okkur/syna v0.17.2 --squash
```

To update it to a newer version, say `v0.18.1` (when it is available), you may use:

```shell
git subtree pull --prefix=themes/syna https://github.com/okkur/syna v0.18.1 --squash
```

See the Github [subtree cheat-sheet](https://github.github.com/training-kit/downloads/submodule-vs-subtree-cheat-sheet/) if you want to learn more about git subtree.
