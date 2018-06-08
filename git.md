# Git

## Aliases
### List
```sh
git config --global alias.i 'init'
git config --global alias.a 'add'
git config --global alias.c 'commit'
git config --global alias.cm 'commit -m'
git config --global alias.co 'checkout'
git config --global alias.cob 'checkout -b'
```

### Creating aliases
#### Command line
```sh
# Single word
git config --global alias.co checkout

# Multiple word
git config --global alias.unstage 'reset HEAD --'
```
#### `.gitconfig`
Aliases can be added directly to your `.gitconfig` file
```
[alias]
	co = checkout
	unstage = reset HEAD --
```
