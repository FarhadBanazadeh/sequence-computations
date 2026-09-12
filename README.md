# Sequence Computations

Research articles, LaTeX sources, computational packages, and reproducibility materials for ternary Collatz-type maps and their scaled families.

**Author:** Farhad Banazadeh
**ORCID:** https://orcid.org/0009-0004-7023-0298

---

## Research Papers & Reproducibility Index

This repository contains the manuscript sources and computational materials associated with ten research works.

For each paper, direct links are provided to the publication record, PDF, LaTeX source, and associated computational or supplementary package.

---

### 1. A Ternary (4k±1)/3 Collatz-Type Map — Computational Study

This research studies the ternary Collatz-type map based on the residue-dependent transformations `(4k−1)/3` and `(4k+1)/3`.

The two Zenodo identifiers below belong to the same underlying research work and are therefore grouped here as a single research entry.

**Zenodo**

* https://doi.org/10.5281/zenodo.22195651
* https://doi.org/10.5281/zenodo.22195652

**Later work**

This computation was subsequently extended to `10^11`:

* [Zenodo 22685074](https://doi.org/10.5281/zenodo.22685074)

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22195652_Ternary_4k_pm_1_over_3_Collatz_Type_Map_up_to_1e9.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22195652_Ternary_4k_pm_1_over_3_Collatz_Type_Map_up_to_1e9.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22195652_Ternary_4k_pm_1_over_3_Collatz_Type_Map_up_to_1e9_Computational_Pack.zip)

---

### 2. A Ternary (4k±1)/3 Collatz-Type Map and Its (4n±4^r)/3 Scaled Family

This work develops a scaled family associated with the ternary `(4k±1)/3` system and studies its powers-of-4 scaling structure.

**Related base DOI**

* https://doi.org/10.5281/zenodo.22195651
* https://doi.org/10.5281/zenodo.22195652

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22228200

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22228200_Ternary_4k_pm_1_over_3_Collatz_Type_Map_and_4r_Scaled_Family.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22228200_Ternary_4k_pm_1_over_3_Collatz_Type_Map_and_4r_Scaled_Family.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22228200_Ternary_4k_pm_1_over_3_Collatz_Type_Map_and_4r_Scaled_Family_Computational_Pack.zip)

---

### 3. A Ternary (4k+1(2))/3 Collatz-Type Map with Two Attracting Cycles

This is an independent compressed ternary Collatz-type system defined on positive integers not divisible by 3.

The finite exhaustive computation through `10^9` identifies two observed attracting cycles:

* `C1 = (1, 2)`
* `C7 = (7, 10, 14, 19, 26, 35, 47)`

The finite computation provides computational evidence and does not constitute a proof of global convergence.

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22279137

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22279137_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_up_to_1e9.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22279137_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_up_to_1e9.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22279137_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_up_to_1e9_Computational_Pack.zip)

---

### 4. A Ternary (4k+1(2))/3 Collatz-Type Map and Its 4^r-Scaled Family

This work develops the `4^r`-scaled family associated with the preceding `(4k+1(2))/3` compressed ternary system.

**Zenodo record**

* https://zenodo.org/records/22639385

**Related base DOI**

* https://doi.org/10.5281/zenodo.22279137

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22639385_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_and_4r_Scaled_Family.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22639385_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_and_4r_Scaled_Family.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22639385_Ternary_4k_plus_1_2_over_3_Collatz_Type_Map_and_4r_Scaled_Family_Computational_Pack.zip)

---

### 5. A Ternary (4k−1(2))/3 Collatz-Type Map: Complete 3-Adic Reduction, Algebraic Cycle Analysis, and Exhaustive Computational Verification up to 10^9

This work studies an accelerated ternary Collatz-type map on positive integers not divisible by 3.

The affine transformation is

`M(x) = 4x − rho(x)`

where

`rho(x) = x mod 3` and `rho(x) ∈ {1,2}`,

followed by complete removal of all powers of 3.

The exhaustive finite computation through `10^9` tests exactly

`666,666,667`

admissible starting values.

Every tested orbit enters one of three observed positive attractors:

* fixed point `1`
* fixed point `2`
* four-cycle `22 → 29 → 38 → 50 → 22`

No unresolved or overflowing trajectory was found in the tested range.

This is finite computational evidence and is not a proof of global convergence for all positive integers.

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22662980

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22662980_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_up_to_1e9.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22662980_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_up_to_1e9.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22662980_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_up_to_1e9_Computational_Pack.zip)

---

### 6. A 4^r-Scaled Family of the Ternary (4k−1(2))/3 Collatz-Type Map: Exact Algebraic Conjugacy, Cycle Preservation, and Transfer of the 10^9 Finite Verification

This work extends the preceding `(4k−1(2))/3` system to its `4^r`-scaled family.

For `x = 4^r y`, the central algebraic relation is

`T_r(4^r y) = 4^r T_0(y)`.

Consequently,

`T_r^j(4^r y) = 4^r T_0^j(y)`.

This gives an exact algebraic conjugacy between the base system and every scaled domain.

The conjugacy transfers orbit structure, periodic cycles, stopping behavior, basin membership, and the finite verification of the base system to the corresponding scaled starting values.

This transfer should not be interpreted as a new exhaustive computation of every integer below `4^r × 10^9`.

**Related base DOI**

* https://doi.org/10.5281/zenodo.22662980

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22671949

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22671949_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_1e9.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22671949_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_1e9.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22671949_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3_Collatz_Type_Map_1e9_Computational_Pack.zip)

---

### 7. Extended Computational Verification of the Ternary (4k±1)/3 Collatz-Type Map up to 10^11: A 128-Bit Exhaustive Certification

This work extends the exhaustive computational verification of the ternary `(4k±1)/3` Collatz-type map from `10^9` to `10^11`.

The additional interval

`10^9 < n ≤ 10^11`

contains exactly

`99,000,000,000`

starting values.

Using a multithreaded C11 implementation with unsigned 128-bit integer arithmetic, every starting value in this interval was certified to descend into the previously verified interval `[1,10^9]`.

The final exhaustive computation produced:

* tested: `99,000,000,000`
* certified: `99,000,000,000`
* unsigned 128-bit overflows: `0`
* maximum steps to the verified base interval: `548`
* corresponding start: `58,528,894,046`
* largest encountered value: `1,030,251,791,629,144,029,921`
* corresponding start: `72,496,238,260`
* peak iteration: `168`

An earlier unsigned 64-bit computation left 158 starts unresolved solely because intermediate orbit values exceeded the 64-bit range. The complete 128-bit rescan eliminated this arithmetic limitation and produced zero overflows.

Combining this certification with the previous exhaustive verification through `10^9` establishes that every starting value

`1 ≤ n ≤ 10^11`

has been computationally verified to reach `1` under this map.

This is a finite exhaustive computational verification and does not constitute a proof of global convergence for all positive integers.

**Related base research**

* https://doi.org/10.5281/zenodo.22195651
* https://doi.org/10.5281/zenodo.22195652

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22685074

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22685074_Ternary_4k_pm_1_over_3_Collatz-Type_Map_up_to_1e11.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22685074_Ternary_4k_pm_1_over_3_Collatz-Type_Map_up_to_1e11.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22685074_Ternary_4k_pm_1_over_3_Collatz-Type_Map_up_to_1e11_Computational_Pack.zip)

---

### 8. Ternary (5k±1)/4 Collatz-Type Map with Two Observed Attractors: Exhaustive Computational Verification up to 10^10 and Algebraic Structure

This work studies the reduced ternary `(5k±1)/4` Collatz-type map on the positive odd integers.

The dynamical system has two observed periodic attractors:

* fixed point `1`
* three-cycle `7 → 9 → 11 → 7`

An exhaustive finite computation was performed for all `5,000,000,000` positive odd starting values below `10^10`.

Every tested starting value entered one of the two displayed attractors. No unresolved trajectory and no additional terminal cycle were encountered within the verified range.

The paper also develops the algebraic structure of the system, including periodic-orbit identities, inverse branches, two-adic valuation statistics, basin structure, and a probabilistic logarithmic-drift model.

This is a finite exhaustive computational verification and does not constitute a proof of global convergence for all positive odd integers.

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22709065

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10_Computational_Pack.zip)

---

### 9. A 5^r-Scaled Family of the Reduced Ternary (5k±1)/4 Collatz-Type Map: Exact Algebraic Conjugacy, Cycle Preservation, Orbit-Statistic Invariance, and Transfer of the 10^10 Finite Verification

This work develops the `5^r`-scaled family associated with the preceding reduced ternary `(5k±1)/4` Collatz-type map.

For every integer `r ≥ 0`, the natural scaled state space is

`S_r = 5^r N_odd`.

Under the scaling map

`Phi_r(y) = 5^r y`,

the reduced maps satisfy the exact relation

`T_r(Phi_r(y)) = Phi_r(T_0(y))`.

Consequently,

`T_r^j(5^r y) = 5^r T_0^j(y)`

for every integer `j ≥ 0`.

This establishes an exact algebraic conjugacy between the base system and every scaled system on its natural scaled domain.

The conjugacy preserves the complete orbit structure, including periodic orbits, minimal cycle lengths, basin membership, transient and capture times, first-descent stopping times, two-adic valuation sequences, inverse-branch structure, and normalized orbit statistics.

The base fixed point and three-cycle therefore become

`5^r → 5^r`

and

`7·5^r → 9·5^r → 11·5^r → 7·5^r`.

The exhaustive finite verification of all `5,000,000,000` positive odd starting values below `10^10` for the base map transfers exactly to the corresponding scaled set

`{5^r y : 1 ≤ y < 10^10, y odd}`

for every fixed `r ≥ 0`.

This is a theorem-based transfer of the base computation. It is not a new independent exhaustive scan of all odd integers below `5^r × 10^10`.

The exact conjugacy is proved on the scaled domain `5^r N_odd`; no equivalent claim is made for arbitrary positive odd integers outside that domain.

**Related base research**

* https://doi.org/10.5281/zenodo.22709065

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22714150

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22714150_5%5Er_Scaled_Family_Ternary_5k_pm_1_over_4_Collatz_Type_Map.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22714150_5%5Er_Scaled_Family_Ternary_5k_pm_1_over_4_Collatz_Type_Map.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22714150_5%5Er_Scaled_Family_Ternary_5k_pm_1_over_4_Collatz_Type_Map_Computational_Pack.zip)

---

### 10. The Reduced 5k + 1(3)/4 Collatz-Type Domain with Four Observed Attractors

This work studies a residue-dependent reduced `5x+c` Collatz-type map on the positive odd integers, referred to as the `5k + 1(3)/4` domain.

For an odd state `x`, the affine correction is selected from `{1,3}` according to the residue class of `x mod 4`, after which all powers of two are removed.

The system has four directly observed periodic attractors:

* fixed point `1`
* three-cycle `31 → 39 → 49 → 31`
* three-cycle `37 → 47 → 59 → 37`
* three-cycle `61 → 77 → 97 → 61`

An exhaustive finite computation tested all `5,000,000,000` positive odd starting values below `10^10`.

Every tested orbit entered one of the four displayed attractors, with zero unresolved cases.

The paper also develops the exact periodic-orbit identity, inverse branches, two-adic valuation distribution, basin statistics, stopping-time and peak records, and a probabilistic contraction analysis.

These algebraic and computational results motivate a Four-Attractor Conjecture. The conjecture is explicitly distinguished from the finite exhaustive verification and is not claimed as a proof of global convergence for all positive odd integers.

**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22726453

**Repository files**

* PDF: https://raw.githubusercontent.com/FarhadBanazadeh/sequence-computations/main/Farhad_Banazadeh_Zenodo22726453_Reduced_5k_plus_1_3_over_4_Collatz_Type_Map_up_to_1e10.pdf
* [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22726453_Reduced_5k_plus_1_3_over_4_Collatz_Type_Map_up_to_1e10.tex)
* [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22726453_Reduced_5k_plus_1_3_over_4_Collatz_Type_Map_up_to_1e10_Computational_Pack.zip)

---

## Research Structure

The ten works belong to **five distinct research lines**.

They use related ternary, residue-dependent, and valuation-based ideas, but they should not be treated as a single dynamical system.

### I. Ternary (4k±1)/3 line

1. Base computational research — Zenodo `22195651 / 22195652`
2. Scaled-family research — Zenodo `22228200`
3. Extended 128-bit exhaustive certification through `10^11` — Zenodo `22685074`

### II. Ternary (4k+1(2))/3 line

4. Base compressed map with two observed attracting cycles — Zenodo `22279137`
5. Its `4^r`-scaled family — Zenodo record `22639385`

### III. Ternary (4k−1(2))/3 line

6. Base accelerated map with three observed positive attractors — Zenodo `22662980`
7. Its exactly conjugate `4^r`-scaled family — Zenodo `22671949`

### IV. Ternary (5k±1)/4 line

8. Base map with two observed attractors and exhaustive verification through `10^10` — Zenodo `22709065`
9. Its exactly conjugate `5^r`-scaled family — Zenodo `22714150`

### V. Reduced 5k + 1(3)/4 line

10. Base residue-dependent reduced map with four observed attractors and exhaustive verification of all `5,000,000,000` positive odd starting values below `10^10` — Zenodo `22726453`

---

## How to Find the Source of a Paper

Researchers should use the **Research Papers & Reproducibility Index** above rather than identify files from filenames alone.

Each research entry provides direct access to:

* the corresponding Zenodo publication or record;
* the compiled PDF;
* the exact LaTeX manuscript source;
* the associated computational or supplementary package.

This structure is intended to make the provenance of every manuscript and computational package immediately identifiable.

---

## Reproducibility Materials

Depending on the publication, this repository contains:

* LaTeX manuscript sources (`.tex`)
* compiled research papers (`.pdf`)
* C source code
* Python verification scripts
* computational summaries
* JSON data
* trajectory and verification outputs
* supplementary archives
* reproducibility ZIP packages
* checksum files

The computational implementation is not identical across all ten research works.

Researchers should consult the specific manuscript and computational package associated with the paper being examined.

---

## Computational Scope

All exhaustive computational statements in these works refer to explicitly stated **finite ranges**.

Verification through `10^9`, `10^10`, `10^11`, or any other finite numerical bound does not by itself constitute a proof of global convergence for all positive integers in the corresponding dynamical system.

Where a scaled-family result is obtained through exact algebraic conjugacy, the result represents an algebraic transfer from the corresponding base system and should not be interpreted as an independent exhaustive scan of every integer below the scaled numerical bound.

---

## Citation

When using a particular mathematical result, manuscript source, computational result, or reproducibility package from this repository, please cite the corresponding Zenodo publication listed in the **Research Papers & Reproducibility Index**.

See also:

* [CITATION.cff](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/CITATION.cff)

---

## Author & Contact

**Farhad Banazadeh**
Independent mathematics researcher

**ORCID:** https://orcid.org/0009-0004-7023-0298

**GitHub:** https://github.com/FarhadBanazadeh

---

## Copyright and Reuse

Copyright © 2026 Farhad Banazadeh.

The research publications represented in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license, subject to the authoritative licensing information associated with each individual Zenodo record.

Under CC BY 4.0, works may be shared and adapted for any purpose, including commercial use, provided that appropriate credit is given to the author, a link to the license is provided, and any changes made are indicated.

**Author:** Farhad Banazadeh
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

For the authoritative publication metadata and licensing information for each work, please consult its corresponding Zenodo record.

---

## Persistent Publication Records

Zenodo provides the persistent publication records and DOI identifiers for the research works represented in this repository.

This GitHub repository serves as a structured source, computational, and reproducibility archive complementing those persistent publication records.
