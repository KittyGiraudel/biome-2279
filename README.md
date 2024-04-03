Reproduction repository for https://github.com/biomejs/biome/issues/2279.

1. Run `yarn install`.
2. `cd` into the `packages/some-dir` directory.
3. Run `yarn biome lint --no-errors-on-unmatched ./src/**/*.tsx`.

This yields an error due to the presence of a comment in the top-level configuration file, despite being authored in JSONC.
