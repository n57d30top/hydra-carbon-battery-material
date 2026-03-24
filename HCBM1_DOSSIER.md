# HCBM-1 Dossier

This is the single technical master document for the public `hcbm-1`
candidate.

It combines:

- material identity
- target properties
- synthesis direction
- provisional recipe hypotheses
- replication guidance
- experimental checklist
- success and fail criteria

## 1. Candidate Identity

- Public ID: `hcbm-1`
- Public Name: `Hydra Carbon Battery Material Candidate`
- Material Family: `hybrid_redox_polymer_scaffold`
- Status: `simulation-only candidate`

`hcbm-1` is the public candidate identity for a CO2-capture material intended
to work by electrically assisted capture and release under bounded operating
conditions.

## 2. Public Thesis

The public thesis is:

> a porous, electrically addressable hybrid redox polymer scaffold can be built
> that selectively captures CO2, remains usable under bounded humidity, and
> releases CO2 again under a conservative electrical swing without relying on
> bulk thermal regeneration as the primary mechanism.

## 3. Functional Requirements

The candidate should be:

- CO2-selective
- bounded-humidity tolerant
- electrically regenerable
- room-temperature-adjacent in operation
- capable of repeated cycling without immediate collapse
- compatible with conductive supports and simple cartridge-oriented geometries

## 4. What The Candidate Is Made Of In Public Terms

The public architecture has four required domains:

1. porous capture domain
2. redox-active domain
3. conductive pathway
4. humidity-management domain

In plain language, `hcbm-1` is not a single declared molecule yet. It is a
candidate built around a constrained architecture.

## 5. Public Synthesis Direction

The preferred first public direction is:

> a porous aromatic polymer or hypercrosslinked polymer scaffold carrying
> redox-active aromatic units, deposited as a thin active layer on a conductive
> carbon support, with partial hydrophobic shielding to improve bounded-humidity
> survivability

### 5.1 Scaffold Direction

Preferred first-pass scaffold classes:

- hypercrosslinked aromatic polymer
- porous covalent polymer network
- porous ladder-like aromatic polymer blend

### 5.2 Redox Direction

Preferred first-pass redox families:

- quinone-like motifs
- imide-like motifs
- phenazine-like conjugated motifs

### 5.3 Conductive Direction

Preferred first-pass support classes:

- carbon paper
- carbon cloth
- graphite felt

Public first preference:

- carbon paper or carbon cloth with a thin active coating

### 5.4 Humidity Direction

Preferred first-pass humidity-management strategies:

- mixed hydrophobic aromatic content
- alkyl-bearing co-component where compatible
- gradient or outer-shell hydrophobic treatment
- humidity-buffering inactive formulation fraction

## 6. Provisional Recipe Hypotheses

These are not final validated recipes.

They are public first-pass hypotheses for researchers who want a more concrete
starting point than a material family statement.

### Recipe Hypothesis R1

`R1` is the preferred public starting point.

- Host direction: porous aromatic or hypercrosslinked aromatic polymer
- Redox direction: quinone-like aromatic functionality tethered into the host
- Support direction: carbon paper
- Humidity direction: mild hydrophobic aromatic or alkyl tuning
- Form factor: thin supported active coating

Public formulation intent:

- robust porous host first
- redox-active content at moderate loading, not maximum loading
- conductive support does most of the current-carrying work
- humidity survivability prioritized over theoretical maximum uptake

### Recipe Hypothesis R2

- Host direction: hypercrosslinked aromatic polymer
- Redox direction: imide-like incorporation
- Support direction: carbon cloth
- Humidity direction: humidity-buffering co-component
- Form factor: thin supported coating or coupon

### Recipe Hypothesis R3

- Host direction: conjugated porous polymer film
- Redox direction: phenazine-like motif family
- Support direction: carbon paper
- Humidity direction: conservative thin-film geometry plus mild hydrophobic
  treatment

## 7. Public Process Direction

The first public process direction is deliberately broad but practical:

1. prepare porous active material or precursor system
2. formulate a thin slurry, ink, or deposition mixture
3. deposit onto carbon paper or cloth
4. dry and stabilize under controlled conditions
5. test in a flat supported coupon geometry

This dossier does not claim the final solved values for:

- exact monomer identities
- exact stoichiometries
- exact solvent systems
- exact polymerization conditions
- exact post-treatment recipe
- exact electrolyte or biasing chemistry

That is deliberate, because those values are not honestly validated yet.

## 8. Public Replication Program

The first serious external program should build a small candidate matrix rather
than one magical sample.

Recommended matrix:

1. two scaffold families
2. two redox motif families
3. two humidity-management strategies
4. one or two conductive supports

Track at least:

- candidate ID
- support type
- loading
- active-layer thickness
- humidity condition
- voltage window
- cycle count

## 9. Public Operating Envelope

Start narrow.

The intended first-pass envelope is:

- concentrated or semi-concentrated CO2-containing stream
- moderate humidity, not saturation
- room-temperature-adjacent operation
- conservative electrical swing
- no bulk thermal regeneration as the primary release path

This is not a claim of direct-air-capture readiness.

## 10. Characterization Requirements

Before claiming progress, collect at least:

- morphology and film quality
- accessible porosity
- baseline conductivity or coupling proxy
- dry CO2 uptake proxy
- humid CO2 uptake proxy
- dry versus humid retention gap
- switching response under conservative electrical conditions
- short-cycle retention

Reasonable tool families include:

- gas sorption methods
- microscopy
- spectroscopy
- electrochemistry such as cyclic voltammetry
- impedance or resistance tracking
- gravimetric or flow-cell measurements

## 11. Experimental Checklist

Use this condensed checklist for the first pass.

### Before Starting

- [ ] confirm everyone understands `hcbm-1` is still `simulation-only`
- [ ] define whether the goal is falsification, screening, or first positive
      signal
- [ ] define controls before building candidates

### Build Phase

- [ ] record candidate IDs
- [ ] record support geometry and loading
- [ ] confirm the conductive pathway is intentional
- [ ] confirm the active layer survives fabrication

### Baseline Tests

- [ ] dry-gas baseline without switching
- [ ] humid-gas baseline without switching
- [ ] compare CO2 condition against control gas

### Switching Tests

- [ ] conservative voltage window only
- [ ] capture-state measurement
- [ ] switched release-state measurement
- [ ] rule out bulk heating as the main cause

### Humidity and Cycling

- [ ] at least one low-humidity condition
- [ ] at least one moderate-humidity condition
- [ ] short repeated cycles
- [ ] reject catastrophic humidity collapse quickly

## 12. Success Criteria

Treat a candidate as encouraging only if all are present:

- measurable CO2-relevant behavior above controls
- electrically associated release behavior
- room-temperature-adjacent operation
- bounded humidity does not immediately destroy function
- short repeated cycling without immediate collapse

## 13. Failure Criteria

Treat the concept as failing first pass if any of these dominate:

- bulk heating is doing the real work
- humidity causes immediate functional collapse
- the switching signal cannot be separated from artifact or noise
- conductivity is too poor for meaningful coupling
- the active phase rapidly delaminates, dissolves, or degrades
- behavior is not meaningfully better than controls

## 14. What This Dossier Still Does Not Claim

This dossier does not claim:

- that the final recipe is solved
- that any listed recipe hypothesis is validated
- that `hcbm-1` is commercially ready
- that physical truth already exists

## 15. Honest Bottom Line

`hcbm-1` is now public in the strongest honest form we can currently support:

- stronger than a vague idea
- stronger than a pure material-family label
- still weaker than a lab-validated final material

If outside researchers can turn this dossier into reproducible humid
electro-swing CO2 behavior, that would be real progress beyond what this
repository itself currently proves.
