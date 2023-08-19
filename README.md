# fuse-native

FUSE bindings for Node JS.

This is a fork of https://www.npmjs.com/package/fuse-native that does
NOT ship libfuse, and instead depends on it being installed on the user's
computer. It also only supports Linux.

URL: https://github.com/sagemathinc/fuse-native

Upstream: https://github.com/fuse-friends/fuse-native

NOTES:

- On ARM64 linux, at least, 3 of the tests fail.
- On x86-64 linux, all the tests pass
- Upstream seems abandoned.
- On ARM64 linux upstream doesn't install, due to the shared library binary that they ship, which is wrong.
