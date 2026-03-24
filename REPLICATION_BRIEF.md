# Replication Brief

This document is the public starting point for researchers who want to inspect,
challenge, simulate, or attempt a first replication-oriented build of
`hcbm-1`.

It is intentionally stronger than the public material summary, but still does
not disclose the internal discovery workflow used inside Hydra.

## 1. Use This Document For

Use this brief if you want to:

- define a first experimental program
- build a first materials screening matrix
- choose characterization methods
- test whether the `hcbm-1` concept fails quickly under realistic constraints

Do not use this document as proof that the material already works.

## 2. Public Research Hypothesis

The public hypothesis is:

> A porous, electrically addressable hybrid redox polymer scaffold can be built
> that selectively captures CO2, remains usable under bounded humidity, and
> releases CO2 again under a conservative electrical swing without relying on
> bulk thermal regeneration as the primary mechanism.

## 3. Minimum Public Architecture

A first replication attempt should include all four functional domains below.

### 3.1 Porous Capture Domain

The active material should include a porous host or porous polymer phase that:

- exposes accessible internal surface area to the gas stream
- allows CO2 transport into the active region
- avoids immediate pore flooding or collapse under moderate humidity

Reasonable first-pass targets:

- predominantly micro/mesoporous regime
- accessible pore widths roughly in the sub-2 nm to low-single-digit-nm range
- film or particulate form that can be integrated onto a conductive support

### 3.2 Redox-Active Domain

The scaffold should contain tethered or embedded redox-active motifs that can
change local binding behavior under an electrical swing.

Reasonable public starting families:

- quinone-like motifs
- imide-like motifs
- phenazine-like or other conjugated redox-capable aromatic units
- redox-active polymer side chains or co-monomers

The public requirement is not a specific molecule, but a redox subsystem that
is:

- electrically addressable
- chemically survivable in repeated switching
- compatible with the porous host

### 3.3 Conductive Pathway

The system needs a conductive pathway so the active phase can actually see the
electrical swing.

Reasonable first-pass options:

- carbon cloth
- carbon paper
- graphite felt
- conductive carbon additive network inside a thin active layer

### 3.4 Humidity-Management Domain

The material should include a humidity-management strategy.

Reasonable public starting approaches:

- partial hydrophobic shielding of non-essential pore surfaces
- core-shell or gradient architectures
- mixed domains where CO2-active regions are protected from direct water
  collapse
- fluorine-free hydrophobic aromatic or alkyl character where compatible

The goal is not zero water uptake. The goal is to avoid immediate functional
failure under bounded humidity.

## 4. What A First Experimental Program Should Build

A useful first replication campaign does not need one perfect candidate. It
needs a small matrix.

Recommended matrix structure:

1. two porous scaffold families
2. two redox motif families
3. two humidity-management strategies
4. two conductive-support strategies

That gives a bounded first matrix without exploding the search space.

## 5. Suggested Public Experimental Variables

### 5.1 Material Variables

- porous scaffold family
- redox motif family
- active-site loading
- conductive additive fraction
- film thickness
- binder choice
- humidity-management treatment

### 5.2 Operating Variables

- CO2 fraction
- relative humidity
- flow rate
- dwell time
- voltage window
- polarity scheme
- switching duration
- cycle count

## 6. Public Starting Envelope

The public concept should be tested first in a narrow operating envelope rather
than under universal capture conditions.

Use a bounded starting regime such as:

- concentrated or semi-concentrated CO2-containing stream, not direct air as
  the first truth test
- moderate humidity, not saturation
- room-temperature-adjacent operation
- conservative electrical swing
- no bulk thermal regeneration as the primary release mode

## 7. Recommended First Characterization Package

Before claiming meaningful progress, a first program should at least gather:

- morphology and film quality
- accessible porosity
- baseline conductivity or electronic coupling quality
- dry CO2 uptake proxy
- humid CO2 uptake proxy
- dry versus humid retention gap
- switching response under conservative electrical conditions
- early cycle retention

Reasonable tool families may include:

- gas sorption methods
- microscopy
- spectroscopy
- cyclic voltammetry or related electrochemical measurements
- impedance or resistance tracking
- gravimetric or flow-cell uptake/release measurements

## 8. First Device-Form Recommendation

For a first build attempt, prefer a simple geometry:

- thin active layer on a conductive planar support
- short diffusion path
- easy gas access
- easy electrical addressing

In practice that means a first-pass geometry like:

- coated carbon paper or cloth
- thin supported film
- flat test coupon rather than a packed industrial cartridge

## 9. Public Success Criteria

A first replication attempt should only be considered encouraging if all of the
following appear together:

- measurable CO2 uptake above control behavior
- measurable electrically associated release behavior
- operation near ambient temperature
- non-catastrophic behavior under bounded humidity
- at least short repeated cycling without immediate collapse

## 10. Public Fail Criteria

Treat the concept as failing the first pass if any of these dominate:

- the signal only works when bulk heating is doing the real work
- humidity causes immediate functional collapse
- the switching signal cannot be separated from noise or artifact
- conductivity is too poor for meaningful electro-swing coupling
- the active phase rapidly delaminates, dissolves, or degrades
- CO2 behavior is not meaningfully different from non-target gas behavior

## 11. What This Brief Still Does Not Provide

This brief still does not provide:

- a single exact synthesis recipe
- a guaranteed monomer list
- a guaranteed support recipe
- a validated electrolyte choice
- a proof that any specific candidate works

That is intentional. This document is a public replication starting brief, not
a claim of completed material truth.

## 12. Honest Research Position

The most honest way to use `hcbm-1` is:

- as a public material target
- as a bounded research direction
- as a candidate family to falsify or strengthen

If a lab or research team can turn this brief into a reproducible material with
credible humid electro-swing CO2 behavior, that would count as real external
progress beyond what this repository currently proves.
