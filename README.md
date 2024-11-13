# Burrito documentation

This documentation includes all the technical high-level documentation of the project,
including development setup, compilation, distribution, deployment, and other relevant
information.

For more in-depth details on how to use mdBook refer to the
[mdBook documentation](https://rust-lang.github.io/mdBook/).

This book consits on one Git submodule per
[project component](./src/overview.md#components). Each submodule contains
a `docs/` directory with the component documentation.

See the [SUMMARY.md](./src/SUMMARY.md) file for the full list of sections.

Clone this repository with:

```bash
git clone --recurse-submodules <url>

# Make sure to update your submodules
bin/sync_modules.sh
```

Build the docs with:

```bash
bin/sync_modules.sh
mdbook build
```
