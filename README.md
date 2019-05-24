Dotfiles managed by chezmoi
====

Getting started
----

These dotfiles are managed through [chezmoi](https://github.com/twpayne/chezmoi). You need to install it before getting these configurations files.

After installing chezmoi:

1- Configure your KeepassXC database path.

```
$ chezmoi edit-config
```

```
[keepassxc]
  database = "/home/user/path/to/database.kdbx"
```

2- Retrieve dotfiles configuration

```
$ chezmoi init git@github.com:franek/dotfiles.git
```

3- See what we will apply

```
$ chezmoi diff
```

4- If you are ok with diff, 

```
$ chezmoi apply
```
