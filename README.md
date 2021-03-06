# GitBoard sample repository

Provides a repository with reasonable data and history to be able to test and demo *GitBoard*.

## Git history

Git history to emulate different valid states of issues.

```
* issue #896                            → done
| * commit with fix of issue #977       → in progress
| branch-without-number
|/
| 895-issue-fix-branch: no commits      → in progress
|/
* issue #870                            → done
* issue #901                            → done
| * commit for issue #894               → in progress; ❗️ not selected
| branch-without-number
|/
| 791-issue-branch: no commits          → in progress
|/
* issue #895
* issue #715                            → done; ❗️ not selected
* issue #977
* issue #575                            → done
* issue #635 (tag: v2.0)                → released (in v2.0)
* issue #459                            → released (in v2.0); ❗️ not selected
* fix of issue #725 (tag: v1.0)         → released (in v1.0)
* issue #725                            → released (in v1.0)
* issue #613                            → released (in v1.0)
|
master branch
```
