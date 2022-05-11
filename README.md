# Semantic Release Example

Example of applying semantic release to node.js package.

Uses:

- semantic-releases - for automatic releases and versioning based on commit messages;
- commitlint - lint and git-hooks for commit messages;
- husky - managing git-hooks;

## Instructions

- commit with `type(source): msg`
- `type` must be one of `[build, chore, ci, docs, feat, fix, perf, refactor, revert, style, test]` [type-enum]

## References:

### Links
https://dev.to/kouts/automated-versioning-and-package-publishing-using-github-actions-and-semantic-release-1kce
https://semantic-release.gitbook.io/semantic-release/usage/getting-started
https://semantic-release.gitbook.io/semantic-release/support/faq

### Repos
[commitlint](https://github.com/conventional-changelog/commitlint)
[semantic-release](https://github.com/semantic-release/semantic-release)