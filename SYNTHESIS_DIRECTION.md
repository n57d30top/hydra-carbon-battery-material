# Synthesis Direction

This document turns `hcbm-1` from a pure material-family statement into a first
public instantiation direction.

It still does not disclose the internal Hydra discovery workflow.

## 1. What `hcbm-1` Is

`hcbm-1` is the public candidate identity for a material in the
`hybrid_redox_polymer_scaffold` family.

That means:

- we do have a candidate
- the candidate is currently expressed as a constrained material class
- we do not yet publish a single final, validated molecular recipe

The purpose of this document is to narrow the public candidate into a plausible
first synthesis direction for external researchers.

## 2. Public Instantiation Strategy

The first public instantiation direction for `hcbm-1` is:

> a porous aromatic polymer or hypercrosslinked polymer scaffold carrying
> redox-active aromatic units, deposited as a thin active layer on a conductive
> carbon support, with partial hydrophobic shielding to improve bounded-humidity
> survivability.

In simpler terms:

- porous polymer backbone
- redox-active CO2-interaction motifs
- conductive carbon support
- humidity-management by surface chemistry and formulation discipline

## 3. Recommended First Public Material Stack

### 3.1 Scaffold Direction

Start from a porous organic scaffold that is:

- chemically robust
- film-compatible or particulate-film compatible
- non-fragile under moderate humidity
- realistic to fabricate without exotic infrastructure

Most reasonable public first-pass directions:

1. hypercrosslinked aromatic polymer
2. porous covalent polymer network
3. porous ladder-like aromatic polymer blend

The point is to begin with a humidity-tolerant polymeric host, not a fragile
high-upside structure as the only path.

### 3.2 Redox Direction

Add a redox-capable subsystem based on aromatic organic motifs such as:

- quinone-like units
- imide-like units
- phenazine-like conjugated units

Public first-pass preference:

- tethered quinone/imide-like content in a porous aromatic polymer environment

Why this direction:

- easier to reason about than a highly fragile crystalline architecture
- more plausible electrical coupling in a thin-film geometry
- more realistic for repeatable formulation work

### 3.3 Conductive Direction

Use a carbon-based support such as:

- carbon paper
- carbon cloth
- graphite felt

Public first-pass preference:

- carbon paper or carbon cloth with a thin active coating

This keeps the first test geometry simple and lowers ambiguity around gas
access and electrical addressing.

### 3.4 Humidity Direction

The first public humidity-management strategy should be conservative:

- reduce catastrophic water sensitivity
- avoid fully sealing the active material
- preserve gas access

Reasonable public first-pass options:

- mixed hydrophobic aromatic content
- alkyl-bearing co-monomer fraction where compatible
- gradient or outer-shell hydrophobic treatment
- humidity-buffering inactive fraction in the formulation

## 4. First Public Candidate Family Matrix

The cleanest first public candidate set is a small matrix, not one magical
recipe.

Recommended first matrix:

### Family A: Quinone-Rich Porous Aromatic Polymer

- porous aromatic scaffold
- quinone-like redox content
- thin coating on carbon paper
- mild hydrophobic tuning

### Family B: Imide-Modified Hypercrosslinked Polymer

- hypercrosslinked aromatic backbone
- imide-like redox-active incorporation
- conductive carbon support
- humidity-buffering co-component

### Family C: Phenazine-Like Conjugated Porous Film

- conjugated porous polymer film
- phenazine-like or related aromatic redox subsystem
- conductive support
- conservative film thickness

## 5. First Public Fabrication Direction

The recommended first public build direction is intentionally simple:

1. prepare porous active material or precursor formulation
2. formulate a thin slurry, coating ink, or deposition mixture
3. deposit onto carbon paper or cloth
4. dry and stabilize under controlled conditions
5. test in a flat supported coupon geometry

This is preferable to starting with:

- thick packed beds
- complex cartridges
- highly optimized industrial geometries

## 6. What We Intentionally Still Do Not Publish

This public direction still does not provide:

- exact monomer identities as a mandated final set
- exact stoichiometries
- exact solvent systems
- exact polymerization conditions
- exact post-treatment recipe
- exact electrolyte or biasing chemistry

That is deliberate.

The goal here is to publish a credible synthesis direction, not to pretend that
the final recipe is already solved.

## 7. How A Researcher Should Use This

Use `SYNTHESIS_DIRECTION.md` together with:

- [MATERIAL_SPEC.md](MATERIAL_SPEC.md)
- [REPLICATION_BRIEF.md](REPLICATION_BRIEF.md)
- [EXPERIMENTAL_CHECKLIST.md](EXPERIMENTAL_CHECKLIST.md)

Interpretation order:

1. `MATERIAL_SPEC.md` tells you what the material is trying to be.
2. `SYNTHESIS_DIRECTION.md` tells you what kind of first candidate family to
   actually build.
3. `REPLICATION_BRIEF.md` tells you what to vary and what to measure.
4. `EXPERIMENTAL_CHECKLIST.md` tells you how to stay honest while doing it.

## 8. Honest Bottom Line

The public candidate is now specific enough to support real external first-pass
materials work:

- porous aromatic or hypercrosslinked polymer host
- quinone-, imide-, or phenazine-like redox functionality
- carbon-paper or carbon-cloth support
- bounded humidity management by formulation and surface tuning

That is more concrete than a generic idea, but still honest about what remains
unsolved.
