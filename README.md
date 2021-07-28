How to greate a git project flow:
https://youtu.be/rX80eKPdA28

for all commands:
git flow

examples:
git flow init
git branch
git flow feature start frank

// to publish and make a pull request on github publish to GitHub

git flow feature finish frank // this will ALSO remove the branch on Github if you changed it
git flow release start 0.1.0
git flow release finish 0.1.0
git flow bugfix start bad
git flow bugfix finish bad

to push all changes at once (can't find it in the vcode GUI:
git push origin --all
git push origin --tags
