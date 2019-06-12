# bashware
bash commands to use across environments

## command line decorate
PS1="[\d \t \u@\w ] $ "

### prior
PS1="[\d \t \u@\h:\w ] $ "

## box tabled file directory tree
alias ftree="find . -type d | sed 's/[^/]*\//|_/g' | more";

alias ls='ls -G'
alias ll='ls -la'

## UNIX Tools
cal

## grep colors ##
export GREP_OPTIONS='--color=auto'
export CLICOLOR=1

### WIP Collation ###

## Apply fuzzy logic at the command line 
[ -f ~/.fzf.bash ] && source ~/.fzf.bash

