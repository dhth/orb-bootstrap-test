# orb-bootstrap-test

This public test repository is a global mise bootstrap configuration for Amp
orbs. Keep credentials, tokens, caches, and project-specific requirements out
of it.

`config.toml` contains the user environment. Keep its tool requests and the
generated `mise.lock` in sync.

`config/` mirrors `~/.config` and is applied as a Git-manifest-backed directory
copy. Only commit public, user-scoped configuration there.
