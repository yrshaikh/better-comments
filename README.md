# better-comments

> A GitHub App built with probot that comments on pull requests that make use of abusive language in comments.

## Usage

Simply [install the app](https://github.com/apps/better-comments) and the bot will keep 👀 on PRs that have abusive comments.

## How it works

When a PR is opened or updated, it will scan through the diffs of files and comment if the PR is adding any abusive comments.

## Development setup

```
# Install dependencies
npm install

# Run the bot
npm start
```
