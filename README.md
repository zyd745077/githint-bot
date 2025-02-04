[GitHint](https://github.com/apps/githint-bot) ensures that your pull requests follow specified conventions.

![](https://camo.githubusercontent.com/7dae22e63277199f47c25ad0911d03d83d6d937e/68747470733a2f2f67697468696e742e6865726f6b756170702e636f6d2f696d616765732f73637265656e73686f74732f70617373696e672d74657374732e706e67)

There are conventions that may not be easily checked with tools like ESLint or Hound CI. These could range from arbitrary checks like `A pull request must be raised by a user whose first name is not more than 6 characters long` to more practical checks like `A pull request must have at least 2 review comments`. GitHint thrives on checking these kinds of conventions.

GitHint fetches metadata about pull requests, commits, branches, trees, and passes the metadata to user-defined scripts for evaluation. Such scripts are expected to return `true` or `false` to determine if a pull request is ready to be merged.

To start using GitHint, first [install the GitHint GitHub app](https://github.com/apps/githint-bot/installations/new) on your repository and add a [.githint.json file](https://githint.herokuapp.com/config) to the root directory of the repository. That's it!

For more info visit the [documentation](https://githint.herokuapp.com/).
