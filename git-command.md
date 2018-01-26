# Git Commands

```javascript
// check to see remote url or push and pull
$ git remote -v || git remote show origin

// change remote url 
$ git remote set-url origin https://github.com/drunkpanda/travel-site.git

// push to remote master branch
$ git push origin master

// see all commits on all branches that aren't pushed yet
// @{u} or @{upstream} means the upstream branch of the current branch 
$ git log @{u}..


```