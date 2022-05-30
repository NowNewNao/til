# 🧙‍&nbsp;Git

- `git add -p`: When you want to cut the hunk into small chunks of code
  - option `s` : Further cut
- `git diff --staged`: You can check the staged part

### aliases that I use quite often in my terminal
```zsh
alias gprmain='git pull --rebase origin main'
alias gsm="git switch main && git pull --rebase origin main"
alias gs='git switch' // gs -c is the command when you crate a new barnch
alias ga.="git add ."
alias gcm="git commit -m"
alias glo='git log --oneline'
alias gsh='git stash'
alias gshp='git stash pop'
alias gst='git status'
alias gr2="git rebase -i head~2" // I have it til head~7
alias gpfhead='git push -f origin head'
alias gbd="git branch --merged|egrep -v '\*|staging|main'|xargs git branch -d" // delete merged branches
```
*I put them in my `.zshrc`
