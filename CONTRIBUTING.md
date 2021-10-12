## Contributing

If you're unsure about an issue or have any questions or concerns, just ask in an *existing issue* or *open a new issue*. If you would like to talk to other contributors and get more context about the project before jumping in, leave a message in the *#hacktoberfest-chat channel* on our discord server.

If you don't have any questions, the issue is clear, and no one has commented saying they are working on the isssue, you can work on it! If you are so inclined, you can open a draft pull request as you continue to work on it. We appreciate any effort on this project!

Development workflow:

* We are working off the ```development``` branch for this project, so be sure to create new branches from it when adding features, fixing bugs, etc.
  * The development branch is set up to autodeploy staging builds of the app. When a PR for the development branch has been opened or merged, you can find a preview for the build [here](https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/deployments/activity_log?environment=Preview)
* Once a PR is merged into the ```development``` branch and everything checks out in the preview, the ```development``` branch will be merged with the ```main``` branch
  * The ```main``` branch is linked to the autodeploy production builds of the app
  * Previews for each production build can be found [here](https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/deployments/activity_log?environment=Production)
  * The current production build of the app can be found [here](https://restaurant-menu-viewer.vercel.app/)

Here are the basic steps to submit a pull request:

1. Claim an issue on [our issue tracker][issues] by commenting on the issue saying you are working on it. If the issue doesn't exist yet, open it. Please only claim one at a time.

1. Fork the [repo] and clone your forked repo locally on your machine.

1. Follow the project's [readme.md](https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/blob/main/README.md) to get setup locally.

1. Run linters and fix any linting errors they brings up.

1. Push to your fork and submit a pull request to the ```development``` branch. Include the issue number (ex. `Resolves #1`) in the PR description. When a PR is opened, a preview of the proposed changes can be found [here](https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/deployments/activity_log?environment=Preview).

1. For any changes, please create a feature branch and open a PR for it to the ```development``` branch when you feel it's ready to merge. Even if there's no real disagreement about a PR, at least one of this project's maintainers needs to look over a PR before merging. The purpose of this review requirement is to ensure shared knowledge of the app and its changes and to take advantage of the benefits of working together changes without any single person being a bottleneck to making progress. We will look over the PR asap and let you know of any improvements or changes that can be made!

Some things that will increase the chance that your pull request is accepted:

* Ensure there are no errors in your code
* Make sure your pull request is detailed (follow our [PR template](https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/blob/main/.github/pull_request_template.md))
* Update the documentation, comments, examples elsewhere, guides, whatever is affected by your contribution

If you are wondering how to keep your fork in sync with the main [repo], follow this [github guide](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork).

[issues]: https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer/issues
[repo]: https://github.com/Self-Taught-Software-Developers/restaurant-menu-viewer
