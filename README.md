# Instructions

1. In a terminal window, run `./runRegistry.sh`
2. In a new terminal window, run `./authRegistry.sh`
3. Run `./publishRelease.sh` to publish the packages initially
4. Commit resulting files
5. Make a change in packageA and commit it
6. Run `rush change` and add a changelog entry
7. Run `./publishPrerelease.sh`
8. Run `npm info @example/packagea`
