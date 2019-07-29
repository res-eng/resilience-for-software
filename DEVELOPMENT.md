This repository uses [pre-commit](https://pre-commit.com/) to lint markdown, enforced on
PRs by [Travis CI](https://travis-ci.org/). Once you have
[installed](https://pre-commit.com/#install) pre-commit, you can locally lint (and
autofix) by running `pre-commit run --all-files` from the root of the repository. You
can add this behavior as a commit hook by running `pre-commit install` once, also from
the repository root.
