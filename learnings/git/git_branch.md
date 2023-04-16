A git branch is a snapshot of your changes.
Similar to a revision in P4 but not really.
For every change you first create a branch that will encapsulate that change.
Process: branch-> work -> work -> work -> merge -> commit
Commands I used for this submission:
- git branch -M learnings
- git add learnings\git\git_branch.md
- git commit -m "learings about git branches"
- git push -u origin learnings