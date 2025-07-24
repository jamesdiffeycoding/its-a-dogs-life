# Just a demonstration project using git

- Here I ran `git add .`, `git commit -m "first commit`, and `git push`.

The push will only affects committed changes.

You can't commit again, even in existing files, without using `git add .` to stage the file changes.

Now let's create a branch with `git branch newbranch` and go to it with `git checkout newbranch`.

Now we're on the new branch. If I  `add., commit and push` let's see what happens.

Doh! You need to `git push --set-upstream origin newbranch` first so they are linked.

This makes the branch viewable in GitHub.

All good so far. I ran a pull request and deleted the branch.

Now let's complicate it by creating two branches at once `git branch one` and `git branch two`.

These won't show in GitHub until a push from main is completed, and their upstream branches are set `git push --set-upstream origin newbranchname`.

This sentence was written on branch one to be pushed and merged into main.

This sentence was written on branch two to be pushed and merged into main.
This sentence was also written on branch two to be pushed and merged into main.


I will undo this commit