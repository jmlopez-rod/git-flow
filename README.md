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

