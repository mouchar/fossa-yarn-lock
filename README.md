# FOSSA scaner issue

This repo exists solely for the purpose of providing a minimal
reproducible example of problem with `yarn.lock` strategy
in NodeJS analyzer.

## What I did
```
yarn add '@babel/cli@^7.13.16'
```

## How to reproduce
```
fossa analyze -o --debug
```
