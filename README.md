# Instructions

1. In a terminal window, run `./runRegistry.sh`
2. In a new terminal window, run `./authRegistry.sh`
3. Run `./publishRelease.sh` to publish the packages initially
4. Make a change in packageA and commit it
5. Run `rush change` and add a changelog entry
6. Run `./publishPrerelease.sh`
7. Run `npm dist-tags ls @example/packagea`
