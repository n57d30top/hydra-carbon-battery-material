# Experimental Checklist

This checklist is the practical companion to
[REPLICATION_BRIEF.md](REPLICATION_BRIEF.md).

Use it to run a first serious evaluation campaign on `hcbm-1` without
overclaiming what the public package proves.

## 1. Before You Start

- [ ] Confirm the team understands that `hcbm-1` is a `simulation-only`
      public candidate, not an experimentally validated material.
- [ ] Confirm the team is testing a bounded concentrated-stream concept, not
      universal direct-air-capture performance.
- [ ] Confirm the team is not expecting a complete synthesis recipe from this
      repository.
- [ ] Define a written first-pass objective:
      `falsify quickly`, `screen candidates`, or `attempt first positive signal`.

## 2. Candidate Matrix Setup

- [ ] Select at least two porous scaffold families.
- [ ] Select at least two redox-active motif families.
- [ ] Select at least two humidity-management strategies.
- [ ] Select at least one conductive support format.
- [ ] Record all candidate IDs before synthesis or fabrication begins.
- [ ] Define one negative control and one simplified non-redox control.

## 3. Build Readiness

- [ ] Confirm all candidate films, pellets, or coupons can be fabricated in a
      repeatable way.
- [ ] Confirm active-layer thickness is measured or estimated.
- [ ] Confirm support geometry and loading are recorded.
- [ ] Confirm mass loading is tracked per candidate.
- [ ] Confirm the conductive pathway is intentional, not accidental.

## 4. Baseline Material Characterization

- [ ] Check whether the active material is physically intact after fabrication.
- [ ] Record morphology and visible defects.
- [ ] Measure or estimate accessible porosity.
- [ ] Measure baseline conductivity or equivalent charge-transport proxy.
- [ ] Check whether the material remains stable during dry hold conditions.
- [ ] Check whether the material remains physically intact under bounded
      humidity exposure before switching tests.

## 5. Gas-Response Baseline

- [ ] Run a dry-gas baseline without electrical switching.
- [ ] Run a humid-gas baseline without electrical switching.
- [ ] Compare CO2-containing feed behavior against an inert or non-target gas
      condition.
- [ ] Check whether any apparent uptake is meaningfully above control behavior.
- [ ] Record whether humidity alone causes immediate loss of function.

## 6. Electrical-Swing Tests

- [ ] Define a conservative voltage window before first switching.
- [ ] Record voltage, current, timing, and polarity scheme for every run.
- [ ] Test capture state under electrical conditions.
- [ ] Test release state under switched electrical conditions.
- [ ] Confirm that observed release is not mainly explained by heating.
- [ ] Record whether the response is reproducible over short repeated runs.

## 7. Humidity Truth Tests

- [ ] Test at least one low-humidity condition.
- [ ] Test at least one moderate-humidity condition.
- [ ] Compare dry and humid uptake behavior.
- [ ] Compare dry and humid release behavior.
- [ ] Flag any immediate pore flooding, collapse, delamination, or signal loss.
- [ ] Reject candidates that fail catastrophically as soon as bounded humidity
      is introduced.

## 8. Cycle Truth Tests

- [ ] Run multiple short cycles for each promising candidate.
- [ ] Track signal drift across cycles.
- [ ] Track physical degradation across cycles.
- [ ] Track whether conductivity worsens across cycles.
- [ ] Track whether humidity accelerates degradation.
- [ ] Reject candidates that lose function almost immediately.

## 9. Artifact Exclusion

- [ ] Check whether the electrical signal could be instrumentation noise.
- [ ] Check whether thermal drift is masquerading as electro-swing behavior.
- [ ] Check whether gas-path transients explain the apparent signal.
- [ ] Check whether support-only or binder-only controls produce similar
      behavior.
- [ ] Do not promote a candidate unless plausible artifacts have been
      challenged.

## 10. Minimum Evidence for A Positive Internal Conclusion

Only treat a candidate as encouraging if all are true:

- [ ] measurable CO2-relevant behavior above controls
- [ ] an electrically associated release response
- [ ] room-temperature-adjacent operation
- [ ] bounded humidity does not immediately destroy function
- [ ] repeated short cycling is possible without immediate collapse

## 11. Immediate Rejection Criteria

Reject or pause a candidate if any of these dominate:

- [ ] function only appears when bulk heating is doing the real work
- [ ] humidity causes immediate collapse
- [ ] the conductive path is too weak for meaningful switching
- [ ] the active layer delaminates, dissolves, or decomposes immediately
- [ ] the signal cannot be separated from artifact or noise
- [ ] behavior is not meaningfully better than controls

## 12. Reporting Package

Before claiming any replication progress, assemble:

- [ ] candidate identifier and composition summary
- [ ] support format and loading summary
- [ ] dry versus humid comparison
- [ ] electrical window used
- [ ] cycle count and retention summary
- [ ] artifact checks performed
- [ ] final disposition:
      `reject`, `watch`, or `promising for deeper study`

## 13. Honesty Rule

- [ ] Do not describe the candidate as validated unless independent evidence
      really supports that claim.
- [ ] Do not describe the public package as a finished recipe.
- [ ] Do not imply commercial readiness from a first positive signal.

The goal of this checklist is not to prove `hcbm-1` works.

The goal is to make the first serious attempts more disciplined, comparable,
and falsifiable.
