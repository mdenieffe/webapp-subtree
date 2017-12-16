# webapp-subtree
Simple webapp with a git subtree so that the style.css can be shared

## Add the subtree 
To add the subtree reference to the project run the following command
git subtree add --prefix subtree/lib https://github.com/mdenieffe/shared-libs.git master --squash

This will pull in the repo into the folder subtree/lib
