## Preparation for creating git ignore

```
$ brew install gibo
$ gibo --version
```

## My gitignore list
- gibo JetBrains >> JetBrains.gitignore
- gibo Rails     >> Rails.gitignore

## Update information

### JetBrains.gitignore
- ADD: .idea/vcs.xml
- ADD: .idea/misc.xml

## Note
- Can't ignore '.idea/workspace.xml'

## How to refrect the latest gitignore
- git rm -r --cached . # delete the git cash
- git add .
- git commit -m "some comment"
- git push origin master
