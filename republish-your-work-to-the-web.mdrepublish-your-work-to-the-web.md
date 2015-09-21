## Republish your work to the web

Look at your `gh-pages` branch. Does it have your work from tasks 4, 5, and 6? How can you check this?

You can use `git branch` to check what branch you are on, `git log` to see a list of commits you have made, and `git checkout <branchname>` to switch between branches.

When two branches have diverged (they have some commits the same and some commits different), you can perform a `merge` to bring the two together. Have a look at the `git merge` section of [this tutorial](https://www.atlassian.com/git/tutorials/using-branches/git-merge). Merge your `master` branch into your `gh-pages`.

First, checkout your `gh-pages` branch like this:

```
git checkout gh-pages
```

Now tell git to bring in your new work from your `master` branch like this:

```
git merge master
```

Now republish your work. If you're not sure how, have a look at [how you published your work the first time](publish-your-code-to-a-website.md#publishing-using-github-pages)?

Don't forget to change back to your `master` branch.
