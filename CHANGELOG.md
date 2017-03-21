# 0.6

* Added `--prune-labels` action to remove unused labels. This action also supports
  `--only-matching REGEX` to limit the pruning behavior and `--ignore-errors` for when
  Google's API times out or returns a 404.

# 0.5.1

* Added `--dry-run` flag for the cautious souls out there

# 0.4

* Added direct interaction with Gmail API (`--upload`, `--prune`, and `--sync`)
* Added support for Travis-CI

# 0.2

* This was the first version released to PyPI.