# Commit Message Guidelines 

We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history.

## Format for git commit messages
We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history.

Each commit message should be formatted in the following way: 

```
<type>(<scope>): <subject>
```
`<type>` and `<subject>` are mandatory, and `<scope>` is optional.

## Type
Must be one of the following:

- **build**: Changes that affect the build system or external dependencies 
- **chore**: Changes that don't affect src( no production code change) or test files
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature (eg. renaming a variable, or changing file location)
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, code documentation, etc)
- **test**: Adding missing tests or correcting existing tests

## Scope
The scope should be the name of the component or file that the commit message is about.

## Subject
The subject contains a succinct description of the change:

- use the imperative, present tense: "change" not "changed" nor "changes"
- don't capitalize the first letter
- no dot (.) at the end

## Examples
```
    feat(cards): add a new feature
    fix(signin): fix bug
    perf(core): performance improvement
    refactor(core): fix typo
    chore(core): fix something
    docs(readme): update docs
    style(src): fix style
    test(core): add tests
    build(core): build something
    chore(core): update something
```
