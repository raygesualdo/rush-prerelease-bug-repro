# Instructions

1. In a terminal window, run `./runRegistry.sh`
2. In a new terminal window, run `./publishRelease.sh`
3. Make a change in packageA and commit it
4. Run `rush change` and add a changelog entry
5. Run `./publishPrerelease.sh`
6. Run `npm dist-tags ls @example/packagea`
