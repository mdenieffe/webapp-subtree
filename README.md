# webapp-subtree
Simple webapp with a git subtree so that the style.css can be shared

## Add the subtree 
To add the subtree reference to the project run the following command
```
git subtree add --prefix subtree/lib https://github.com/mdenieffe/shared-libs.git master --squash
```

This will pull in the repo into the folder subtree/lib

## Push our changes back to the subtree

To push our changes back to the subtree repo run the following command
```
git subtree push --prefix subtree/lib https://github.com/mdenieffe/shared-libs.git master
```

## Pull latest change from the subtree repo

```
git subtree pull --prefix subtree/lib https://github.com/mdenieffe/shared-libs.git master
```
