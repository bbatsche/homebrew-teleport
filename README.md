# Version Specific Teleport Tap

This repository has version specific formulae for [Gravitational Teleport](https://gravitational.com/teleport/). Teleport authentication & proxy servers are not necessarily forwards compatible with newer versions of the client, so depending on the version running within your cluster(s) you may need a specific version locally. This is currently only documented as a [Github issue](https://github.com/gravitational/teleport/issues/1661). Figure out what version you need and install it with:

```bash
brew tap bbatsche/teleport
brew install teleport@<version>
```

You can either update your `$PATH` for the version of Teleport installed, or you can tell Homebrew to link a version for you:

```bash
brew link --force teleport@<version>
```

## Versions

- [Teleport 1.3](https://gravitational.com/teleport/docs/1.3/user-manual/)
- [Teleport 2.0](https://gravitational.com/teleport/docs/2.0/user-manual/)
- [Teleport 2.3](https://gravitational.com/teleport/docs/2.3/user-manual/)
- [Teleport 2.4](https://gravitational.com/teleport/docs/2.4/user-manual/)
- [Teleport 2.5](https://gravitational.com/teleport/docs/2.5/user-manual/)

_**Note:** Teleport 2.5 is the current stable version installed by default through Homebrew. It's included here for debugging purposes and completeness, but should be installed through regular formula in Homebrew Core._
