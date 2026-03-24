# Hydra Carbon Battery Material

Public release package for the material-side output of the Hydra Carbon Battery
program.

This package intentionally publishes the material concept only.

It does not publish:

- the discovery workflow
- internal search or ranking logic
- reject or promotion logic
- internal system or deployment models
- internal runtime artifacts from the Sovryn repository

## Public Candidate

- Public ID: `hcbm-1`
- Public Name: `Hydra Carbon Battery Material Candidate`
- Material Class: `hybrid_redox_polymer_scaffold`
- Status: `simulation-only`
- Intended Use: electrically regenerable CO2 capture material for bounded,
  controlled concentrated gas streams

## Public Thesis

`hcbm-1` is a porous, electrically addressable hybrid redox polymer scaffold
intended to bind CO2 selectively at room-temperature-adjacent conditions and
release it again through an electrical swing, without relying on bulk thermal
regeneration as the primary mechanism.

The public design target is a material family that is:

- CO2-selective
- humidity-tolerant
- electrically regenerable
- cycle-capable
- compatible with conductive supports and cartridge integration

## License

This package is released as open-source software under the Apache License 2.0.

See [LICENSE](LICENSE) for the exact terms.

## What This Package Contains

- [HCBM1_DOSSIER.md](HCBM1_DOSSIER.md)
- [material-spec.json](material-spec.json)
- [DISCLAIMER.md](DISCLAIMER.md)
- [PUBLISHING.md](PUBLISHING.md)
- [LICENSE](LICENSE)
- [NOTICE](NOTICE)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md)

## What This Package Does Not Claim

- no wet-lab synthesis has been performed for this package
- no experimental performance data is included
- no deployment or commercial-readiness claim is made
- no claim is made that `hcbm-1` is the only viable material path

## For Researchers

If you want the single technical document for the candidate, use
[HCBM1_DOSSIER.md](HCBM1_DOSSIER.md).

It combines:

- material identity
- synthesis direction
- provisional recipe hypotheses
- replication guidance
- experimental checklist
- success and fail criteria

## Archive Integrity and Blockchain Anchor

The canonical release archive hash must be recorded outside the archive itself.

That is intentional: if the archive hash were written into this README before
packaging, the archive digest would change again.

For that reason:

- this README can state the archive-anchor policy
- the final archive hash should be published in a separate release record
- blockchain anchoring should only be claimed after a real onchain transaction
  exists

Current anchor status for this package:

- archive anchor: pending external Base L2 submission

## Release Boundary

This package is designed to be extracted and committed as its own public GitHub
repository or published as a standalone public folder.

The intended release boundary is:

- publish this folder
- do not publish the internal Hydra discovery and optimization stack with it

See [PUBLISHING.md](PUBLISHING.md) for the exact boundary.
