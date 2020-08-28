# Git Hooks


Create and share with team git hooks, steps:


1 - Create .githooks directory

2 - Put shell hook script inside folder

3 - Change hook path config

```
git config --global  core.hooksPath .githooks
```


On this project I put pre-push hook to execute unit tests.