# Just a demonstration project using git

- Here I ran `git add .`, `git commit -m "first commit`, and `git push`.

The push will only affects committed changes.

You can't commit again, even in existing files, without using `git add .` to stage the file changes.

Now let's create a branch with `git branch newbranch` and go to it with `git checkout newbranch`.

Now we're on the new branch. If I  `add., commit and push` let's see what happens.

Doh! You need to `git push --set-upstream origin newbranch` first so they are linked.