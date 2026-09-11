# orb-bootstrap-test

This public test repository is a global mise bootstrap configuration for Amp
orbs. Keep credentials, tokens, caches, and project-specific requirements out
of it.

`config.toml` contains the base user environment. Files named
`config.remote-env-*.toml` are composable presets selected by caller projects.
Keep tool requests and their generated lockfiles in sync.
