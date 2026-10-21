# KihaWorld Launcher

Download the newest version from
[Releases](https://github.com/UADominator/LauncherRelease/releases/latest).
Install instructions and the source code are in the
[launcher repository](https://gitlab.com/dominator_git/infrastructure/launcher).

## Code signing policy

**Status: in progress.** Until then the Windows exe has no code signature.

Free code signing provided by [SignPath.io](https://about.signpath.io),
certificate by [SignPath Foundation](https://signpath.org).

- The Windows exe will have an Authenticode signature from SignPath Foundation.
- The Linux packages have no code signature.
- The `.sig` files and `latest.json` let the launcher check its own updates.

The launcher CI pipeline builds and publishes every file. Team roles and the
privacy policy are in the
[launcher repository](https://gitlab.com/dominator_git/infrastructure/launcher#code-signing-policy).
