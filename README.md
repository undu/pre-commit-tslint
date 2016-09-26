tslint mirror
================

Mirror of tslint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For tslint: see https://github.com/palantir/tslint

### Using tslint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/unduthegun/pre-commit-tslint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: tslint

