#### To list all remote branches with Author name using CLI
```
git for-each-ref --format= '%(authorname) %09 %(refname)' --sort=authorname
