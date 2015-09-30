## T1 Create Red and Green Blocks

> This task requires HTML & CSS

Create a file called `task1.html` that looks something like this:

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>

	<style type="text/css">
	/* CSS goes here */
	</style>
</head>
<body>
	<!-- HTML goes here -->
</body>
</html>
```

Now you'll write some CSS in the `style` tag in the `head` of the HTML file. Create two blocks that are `10em` wide. The first block should have a red background, and say "stop." The second block should have a green background, and say "go." Both blocks should have white text.

### Use git to add your files

Run `git status` to see what has changed. You should see something like:

```
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	task1.html

nothing added to commit but untracked files present (use "git add" to track)
```

Now run `git add task1.html` to track that file. That tells git about the file, and tells it to watch it for changes.

If there files that you don't want git to track, don't add them using `git add`. For example: you might see `task1.html~`. That's a local back up file created by your computer, so you don't need to `git add` it.

To commit your changes to git, run `git commit -m "task 1 is done"`.

To push your changes to GitHub, run `git push -u origin master`

---

[Go back to Let's Code](lets_code.md) or [go on T2 Colour the blocks](colour-the-blocks.md)
