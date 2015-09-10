## Publish your code to a website

Now let's use github pages to publish (https://pages.github.com/) your work to a website.

You will need to create a branch of your code called `gh-pages`.

Before you do that let's explore branching in github... `todo add some info about branching - they covered it in git-it already...`

In your project folder type:

`git branch`

You should see only one branch called `master`

Now create a new branch called `gh-pages` by typing this in the terminal:

`git branch gh-pages`

To move into that branch type:

`git checkout gh-pages`

Any work you commit now will be done in the gh-pages branch. We will be using this branch to publish the work you are doing to github pages, to a page http://username.github.com/RedAndGreen.

To push this branch to github type:

`git push origin gh-pages`

After you've done this you should check out the master branch again by doing:

`git checkout master`

After the above steps the work you've done so far will be available online at: `http://username.github.com/RedAndGreen`

---

[Go back to Let's Code](lets_code.md)
