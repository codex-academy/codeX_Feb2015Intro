## Git Ignore

You won't always want to add every file in a directory to your git repository. Extra files like local backups, local caches of files, variables that just apply to your terminal set up don't need to be added to your git repository: they're only needed on your machine.

You can add just the files you want using `git add` for each file. Sometimes you want to add lots of files in one go, but tell git to ignore some files or a particular folder. If you want to tell git to ignore a file forever (to never add it), you can list it in a special `.gitignore` file.

If you wanted to ignore any files in a directory called `tmp`, your `gitignore` would look like this

```
tmp
```

If you wanted to ignore any files that end with `~`, your `gitignore` would look like this

```
*~
```
