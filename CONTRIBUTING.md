# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

Please note we have a [CODE of CONDUCT](https://github.com/chryz-hub/web-dev-resources/blob/master/CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.


## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a 
   build.
2. Update the README.md with details of changes to the interface, this includes new environment 
   variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you 
   do not have permission to do that, you may request the second reviewer to merge it for you.

## <a name="commit"></a> Commit Message Guidelines 😎

In order to make git commit messages **easier to read** and faster to reason about, we follow some guidelines on most commits to keep the **format predictable**. Check [Conventional Commits specification](https://conventionalcommits.org) for more information about our guidelines.

**Examples**:


```
docs(changelog): update changelog to beta.5
docs: add API documentation to the bot
test(server): add cache tests to the movie resource
fix(web): add validation to phone input field
fix(web): remove avatar image from being required in form
fix(release): need to depend on latest rxjs and zone.js
```

### Type

Must be one of the following:

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
- **ci**: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests
