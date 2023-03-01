# Summary

GitHub action for publishing packages and documentation to Hackage.

It is a fork of [haskell-actions/hackage-publish](https://github.com/haskell-actions/hackage-publish). In difference to the original it:

- Fixes the issues of the original action not failing on errors such as unsuccessful publishing.
- Automatically generates the artifact to upload using Cabal.
- Simplifies by not dealing with documentation at all.
