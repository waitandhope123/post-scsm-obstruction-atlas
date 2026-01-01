# Quantum Gravity Error Correction (QGEC)
## Repo 1 — Feasibility & Constraint Mapping

This repository does **not** propose a theory of quantum gravity or a concrete
error-correcting code.

Its sole purpose is to determine **whether QEC-like protected information is
even *formulable*** under increasingly strict physical requirements, culminating
in background-free, fully diffeomorphism-invariant settings.

Negative results are treated as **first-class outcomes**.

---

## Repository Structure

The repo is organized as a **linear investigation**, divided into four phases:

1. **Calibration** — remove definitional ambiguity  
2. **Baselines** — show QEC works *when strong scaffolding is present*  
3. **Stress Tests** — remove or enforce constraints one by one  
4. **Synthesis** — map obstructions and state final conditional results  

Each “toy” is **declarative**, not a simulation.

---

## Calibration Phase (T01–T05)

Purpose: eliminate equivocation and make all structural assumptions explicit
*before* any claims are made.

### T01 — Definition Calibration
Enumerates the major meanings of “error correction” used in physics and records
the structural assumptions each meaning requires.

Key rule:
> If assumptions differ, the notion of “error correction” differs.

---

### T02 — Trivial Invariant False-Positive Calibration
Separates **invariants** from **error-corrected information**.

Operational screening criteria (minimal, not sufficient):
1. Nontrivial logical distinguishability
2. Recoverability after a specified disturbance
3. Logical addressability / decoding

Result:
> Invariance alone ≠ error correction.

---

### T03 — Code Subspace Minimality Calibration
Makes explicit the dependency chain:

```
code subspace
→ encoding map
→ logical distinguishability
→ addressability
→ recovery
```

Records which assumptions are required to even *state* each link.

---

### T04 — Noise Definition Dependency Calibration
Enumerates common meanings of “noise” and the assumptions each requires.

Key principle:
> If “noise” is undefined, then “error correction” is undefined.

---

### T05 — Assumption Taxonomy Calibration
Consolidates **all assumptions** introduced in T01–T04 into a single registry
(grouped by background, locality, observer, gauge, boundary, semiclassical).

No conclusions are drawn.

---

## Baseline Phase (T06–T10)

Purpose: demonstrate that QEC works **when strong textbook assumptions are
explicitly present**, without claiming they are fundamental.

---

### T06 — Standard QEC on Fixed Background
Assumes:
- fixed background geometry
- preferred time
- subsystem factorization
- locality
- external observer / environment

Result:
> Standard QEC is well-defined and operational *given these assumptions*.

---

### T07 — Local Noise vs Subsystem Factorization
Toggles **subsystem factorization** while keeping other baseline assumptions.

Result:
> Without factorization, local-noise QEC notions become undefined.

---

### T08 — Holographic QEC with Boundary Structure
Assumes:
- fixed asymptotic boundary
- semiclassical bulk
- partial gauge fixing

Result:
> Holographic-style QEC is well-defined *only because* these structures exist.

---

### T09 — Semiclassical Gravity without Boundary
Removes boundary structure while retaining a semiclassical regime.

Result:
> Boundary-anchored constructions (e.g. entanglement wedge reconstruction)
collapse without a boundary.

---

### T10 — Effective Error Correction Only
Classifies QEC-like notions as:

- **effective-only**, or
- **candidate-fundamental**

Rule:
> If a notion relies on time, locality, factorization, observers, boundaries,
> or semiclassical structure, it is labeled *effective-only*.

---

## Stress Test Phase (T11–T15)

Purpose: remove baseline scaffolding or enforce invariance constraints to see
which QEC notions survive.

---

### T11 — Remove Fixed Background
Makes geometry dynamical while keeping other baseline structure.

Result:
> Locality, subsystem structure, and recovery notions destabilize immediately.

---

### T12 — Remove Local Noise Definition
Removes the **noise interface**, not time or observers.

Result:
> The core QEC claim “this code corrects this noise” collapses if noise is undefined.

---

### T13 — Enforce Full Diffeomorphism Invariance
Requires that **only gauge-invariant structures count as physical**.

Result:
> Subsystems, locality, noise models, recovery maps, and logical operators
lose invariant meaning.

---

### T14 — Dynamic Geometry Code Instability
Focuses on code-subspace stability under fluctuating geometry.

Result:
> Even if a code exists semiclassically, dynamical geometry generically
destabilizes its identification.

---

### T15 — Gauge Constraint Logical Operator Mixing
Enforces gauge constraints and examines operator identification.

Result:
> Logical operators become gauge-relative and mix with dressing/constraint data.

---

## Synthesis Phase (T16–T20)

Purpose: consolidate results into explicit feasibility statements.

---

### T16 — Minimal Requirement Set
Extracts the **minimal structural atoms** required to even formulate QEC-like
protected information.

If any atom cannot be defined gauge-invariantly, QEC cannot be fundamental.

---

### T17 — “Only If Subsystem Structure”
Conditional necessity:

> QEC-like protected information is **only possible if**
> some stable subsystem-like (or equivalent) structure exists.

---

### T18 — “Only If Boundary / Anchor Structure”
Second conditional necessity:

> QEC-like protected information is **only possible if**
> some invariant anchoring structure stabilizes subregions and operators.

Currently known example: fixed asymptotic boundaries.

---

### T19 — Hard vs Soft Obstruction Map
Classifies obstructions as:

- **HARD** — not formulable under required invariance
- **SOFT** — no known surviving construction (yet)

Used as input to the final closure.

---

### T20 — Final No-Go or Conditional Result
Final outcome:

**Hard result**
- In strictly background-free, fully diffeomorphism-invariant settings,
  QEC-like protected information is **not formulable**.

**Conditional permission**
- QEC-like protection is possible *only if* strong, explicit,
  non-fundamental scaffolding is present (subsystems, anchoring, noise interface).

No known framework provides these structures without reintroducing
effective or background-dependent elements.

---

## Repo 1 Conclusion

The feasibility space for quantum-gravity error correction is either:

- **empty**, or  
- **sharply constrained** to regimes with strong, explicit, non-fundamental structure.

Any future theory-building must explicitly accept or evade these constraints.
