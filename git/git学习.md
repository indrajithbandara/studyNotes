## git学习
一、git配置
```linux
[user]
    name = xyzoer
    email = ttghost@126.com
[color]
    ui = true
    log = true
    interactiove = true
    branch = true
    status = true
    diff = true
[core]
    excludesfile = /Users/fish/.gitignore_global
[difftool "sourcetree"]
    cmd = opendiff \"$LOCAL\" \"$REMOTE\"
    path =
[mergetool "sourcetree"]
    cmd = /Applications/SourceTree.app/Contents/Resources/opendiff-w.sh \"$LOCAL\" \"$REMOTE\" -ancestor \"$BASE\" -merge \"$MERGED\"
    trustExitCode = true
[push]
    default = matching
[alias]
    co = checkout
    br = branch
    ci = commit
    st = status
    pl = pull
    ps = push
    dt = difftool
    l = log --stat
    cp = cherry-pick
    ca = commit -a
```
