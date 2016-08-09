# ue4-git-lfs-diff-bug-example
Example of bug/missing feature reported here: https://answers.unrealengine.com/questions/466658/git-lfs-diff-not-working.html

## Steps to reproduce
1. Open project.
2. Ensure git version control is enabled.
3. Change `Content/DiffTestBP` -- e.g. add a `Tick` event -- then compile and save.
4. From *File -> Diff* select the existing commit to diff against.
5. `Unable to load assets to diff. Content may no longer be supported?` should be displayed.
