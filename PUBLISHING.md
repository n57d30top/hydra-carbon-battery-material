# Publishing Boundary

This folder is intended to be the GitHub-commit-ready public boundary for the
Hydra Carbon Battery material release.

## Publish

Publish the contents of this folder, or extract this folder into a separate
repository root.

## Do Not Publish With This Package

Do not bundle the internal Hydra discovery stack with this package.

Keep private:

- internal search workflows
- internal scoring and ranking machinery
- reject and promotion logic
- internal sweeps and optimization levers
- internal product, cartridge, system, and deployment program internals
- runtime artifacts, reports, and operator state from the Sovryn repository

## Public Position

The public claim is limited to:

- the material family
- the public material identity
- the target property envelope
- the honest `simulation-only` status

## Recommended Commit Shape

Recommended public repository root:

- `README.md`
- `MATERIAL_SPEC.md`
- `material-spec.json`
- `DISCLAIMER.md`
- `LICENSE`
- `NOTICE`

This package is intentionally small so it can be committed cleanly without
bringing along internal repository history or unrelated program state.

## Integrity Note

If you create a release ZIP from this package and want to anchor its hash on a
blockchain, publish the final archive hash in a detached release record after
the archive is built.

Do not edit the package contents to insert the archive hash before packaging,
because that would change the archive digest.
