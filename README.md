# git-cloud-examples-nennen

Small, original example files for practicing the basics of Git. They are intended
as hands-on exercises alongside *Git und Github Crashkurs*; they do not reproduce
the book's content.

## Try it

Start by checking the repository and editing one of the example files:

```sh
git status
git diff
git add beispiele/ideen.txt
git commit -m "Add an idea"
```

To practice branches, create a branch, change an example, and commit the change:

```sh
git switch -c neue-idee
git add beispiele/aufgaben.txt
git commit -m "Add a practice task"
```

You can then switch back to the branch you started from (often `main` or
`master`) and merge the new branch:

```sh
git switch main
git merge neue-idee
```

If your starting branch has a different name, use that name instead of `main`.
