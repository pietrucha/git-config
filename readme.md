# GIT configuration

### 1. graphical log

```bash
$git config --global alias.grog 'log --graph --abbrev-commit --decorate --all --format=format:"%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)"'
```


### 2. stash

`git stsh` - stash only unstaged changes to tracked files, 

`git stash` - stash any changes to tracked files,

`git staash` - stash untracked and tracked files,  

`git staaash`s - stash ignored, untracked, and tracked file
```bash
$git config --global alias.stsh 'stash --keep-index'
$git config --global alias.staash 'stash --include-untracked'
$git config --global alias.staaash 'stash --all'
```
### 3. short status
```bash
$ git config --global alias.shorty 'status --short --branch'
```

### 4. forget to add file in last commit
```bash
$ git config --global alias.commend 'commit --amend --no-edit'
```


