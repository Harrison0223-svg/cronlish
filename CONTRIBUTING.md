# Contributing

Keep each topic branch focused. Include a reproducible synthetic fixture, expected and actual results, and exact test commands. Do not include private data, secrets, or unlicensed assets. Add a regression test for changes in behavior. Disclose material AI assistance and review the diff yourself before submitting.

## Fork scope and checks

For a fork-local change, select Harrison0223-svg/cronlish as both head and base repository. For upstream contributions, follow upstream instructions; do not use an upstream issue-closing reference in a fork-local PR.

Use the standard library for runtime code, type public functions, and keep existing output deterministic. See [AGENTS.md](AGENTS.md).

With pytest installed:

    python -m pytest -q
