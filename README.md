# bash-scripts

## move your files to dir

`mkdir ~/.bin && cp -R ./git ~/.bin` OR `cp -R ./git ~/.bin`

## make an entire directody executable

`chmod +x ~/.bin/git/*`

## add lines to ~/.gitconfig

`vim ~/.gitconfig`

```
[alias]
    example = "!$HOME/.bin/git/example"
    branches = "!$HOME/.bin/git/branches"
    bs = branches
    my-branches = "!$HOME/.bin/git/my-branches"
    mbs = my-branches
```

# Dev

## make an entire directody executable

`chmod +x ./git/*`
