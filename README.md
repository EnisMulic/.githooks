# Githooks

A sample project to setup githooks that are managed along with a `git` repository

[Documentation](https://git-scm.com/docs/githooks)

## Requirments

* Git >= 2.9.0

## How to setup

To setup githooks you can include the shareable `.gitconfig` into your local repository by running 

```bash
git config --local include.path ../.gitconfig
```

or just configure the path to the `.githooks` folder with:

```bash
git config --local core.hooksPath .githooks
```

## How to enable githooks

To enable a specific hook remove the `.sample` from its corresponding script