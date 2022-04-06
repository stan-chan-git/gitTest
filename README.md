git pull
-->
git -c core.quotepath=false -c log.showSignature=false fetch origin --recurse-submodules=no --progress --prune
git -c core.quotepath=false -c log.showSignature=false merge origin/master --no-stat -v
