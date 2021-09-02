# git-flow

Repository to showcase the usage of m.

## Releases

From the `develop` branch:

1. run `releaseSetup.sh`
2. Edit CHANGELOG.md
3. run `submitReleasePullRequest.sh`.

First merge the pr with title `(release) x.x.x`. After the build is
succesful and a new artifact has been published. Merge the next one
with the title `(release to develop) x.x.x`.

## Hotfixes

From the `master` branch:

1. run `hotfixSetup.sh`.
2. Edit CHANGELOG.md
3. Fix the issues
4. run `submitReleasePullRequest.sh`.

First merge the pr with title `(hotfix) x.x.x`. After the build is
succesful and a new artifact has been published. Merge the next one
with the title `(hotfix to develop) x.x.x`.

## Status

Branch protections can be created in order to prevent developers from merging.
