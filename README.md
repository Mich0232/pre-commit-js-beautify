JS Beautify for pre-commit
========================

JS Beautify for pre-commit>=2.0.0.

For pre-commit: see https://github.com/pre-commit/pre-commit

For JS Beautify: see https://github.com/beautify-web/js-beautify


## Using JS Beautify with pre-commit

Add this to your `.pre-commit-config.yaml`:
```yaml

-   repo: https://github.com/Mich0232/pre-commit-js-beautify.git
    rev: 1.14.8 # represents the used version of JS Beautify as well
    hooks:
    -   id: js-beautify
        args: [] # list of arguments like '--editorconfig', '--end-with-newline', '--wrap-attributes=auto', '--wrap-line-length=120'
 ```
