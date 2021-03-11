# bash

## get process by username
```sh
top -b -n 1 -u oracle
```

## configure alias for short keys
```sh
alias l.='ls -d .* --color=auto'
alias ll='ls -l --color=auto'
alias ls='ls --color=auto'
alias vi='vim'
alias which='alias | /usr/bin/which --tty-only --read-alias --show-dot --show-tilde'
```

## find and 1st occur quit
```sh
find . -name teste.xml -print -quit
```

## Extracting .tar.gz files
```sh
tar xvzf file.tar.gz
```

## Compress .tar.gz files
```sh
tar zcvf file.tar.gz file/
```