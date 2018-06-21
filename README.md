ruby-lint mirror
================

Mirror of ruby-lint gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For ruby-lint: see https://github.com/YorickPeterse/ruby-lint


### Using ruby-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-ruby-lint
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: ruby-lint
