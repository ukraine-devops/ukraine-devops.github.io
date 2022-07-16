### install golang onto your laptop
https://go.dev/dl

### install hugo engine on Windows with choco
```
choco install hugo-extended -confirm
hugo version
```
### clone repository with SSH key
`git clone git@github.com:ukraine-devops/ukraine-devops.github.io.git`

### update theme as submodule in repository
`git submodule update --init --recursive`

### create new post or go to the next step
`hugo new posts/my-new-post.md`

### use interactive server for hot reload editing
`hugo server -D`

### push changes to origin
`git add . && git commit -m "changes" && git push`

### or do it in one command with git alias: 
`cmp = "!f() { git add -A && git commit -m \"$@\" && git push; }; f"` 
