#Sign your commits using GPG

By now, you should have [generated a GPG key](https://github.com/pn101/instructio4/blob/master/GPG%20key/generategpg.md) and [added the GPG key to GitHub](https://github.com/pn101/instructio4/blob/master/GPG%20key/addgpg.md)

Follow the next steps to sign your commits using GPG:

1. When commiting changes in your local branch, add the `-S` flag to the git commit command:
```
$ git commit -S -v
```
2. After your commit, provide your passphrase you set up when you [generated a GPG key](https://github.com/pn101/instructio4/blob/master/GPG%20key/generategpg.md)
3. `push` your commits to the remote repository on GitHub
```
$ git push origin master
```
4. Navigate to GitHub to see your recent commits. You will see your `verified` commits
