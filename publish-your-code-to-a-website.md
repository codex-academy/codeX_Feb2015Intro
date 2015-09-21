## Publish your code to a website

Now we're going to publish your work to a website, using [GitHub Pages](https://pages.github.com/). If you have a git branch called `gh-pages` in a repository that you have pushed to GitHub, GitHub will publish the static HTML, CSS, and JavaScript for you at at `<username>.github.io`. You can use this for any static content, but not for apllications that require a server.

## Branches

In the terminal, change to your project folder and type

```
git branch
```

to see a list of your branches. You should see only one branch called `master`.
Now create a new branch called `gh-pages`, like this:

```
git branch gh-pages
```

This tells git to make a new branch called `gh-pages` based on your current branch (which is `master`).

Now do `git branch` again. What do you see? Does `git branch` tell you which branch you are on?

To move into your new branch, type:

```
git checkout gh-pages
```

Any commits you make now will be on the `gh-pages` branch (and won't show up on `master`). You'll be using this branch to publish the work you are doing to [GitHub Pages](https://pages.github.com/).

## Publishing using GitHub Pages

To push this branch to github type:

```
git push origin gh-pages
```

GitHub notices that you've pushed a branch called `gh-pages`, takes the HTML, CSS, and JavaScript, and publishes it. This can take a minute or two. Your RedAndGreen work is now published at https://&lt;username&gt;.github.io/RedAndGreen.

After you've done this you should checkout the master branch again by doing:

```
git checkout master
```

---

[Go back to Let's Code](lets_code.md)
