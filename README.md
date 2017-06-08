# AppDecompileTools

AppDecompileTools is a tool that supports decompiling of applications. Aggregate tools for decompiling Android, iOS, Unity projects, provide shell scripts to process them consistently and improve usability. It can be easily customized.

## Documentation

- The [Android tools] provides a decompiler for Android projects(.apk)).
- The [iOS tools] provides a decompiler for iOS projects(.ipa)).
- The [Unity tools] provides a decompiler for Unity projects(.apk and .ipa)).
- The [release notes] document the major changes in each release.

### Project branches

- The project has `dev-vX` and `release-vX` branches, where `X` is the major version number.
- Most development work happens on the `dev-vX` branch with the highest major version number. Pull requests should normally be made to this branch.
- Bug fixes may be submitted to older `dev-vX` branches. When doing this, the same (or an equivalent) fix should also be submitted to all subsequent `dev-vX` branches.
- A `release-vX` branch holds the most recent stable release for major version `X`.

[Android tools]: https://github.com/mofneko/AppDecompileTools/blob/dev-v1/README.md
[iOS tools]: https://github.com/mofneko/AppDecompileTools/blob/dev-v1/README.md
[Unity tools]: https://github.com/mofneko/AppDecompileTools/blob/dev-v1/README.md
[release notes]: https://github.com/mofneko/AppDecompileTools/blob/dev-v1/RELEASENOTES.md
