# githooks
Example setup with flake8 + pre-commit + travis CI


configure flake8 with git

    git config include.path '../.gitconfig'

`hooks/pre-commit` triggers all `hooks/pre-commit.*` hooks

    mv .git/hooks .git/hooks_bac
    ln -fs ../hooks/ .git
