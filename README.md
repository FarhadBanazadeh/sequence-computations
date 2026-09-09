# Sequence Computations

Research articles, LaTeX sources, computational packages, and reproducibility materials for ternary Collatz-type maps and their scaled families.

**Author:** Farhad Banazadeh
**ORCID:** https://orcid.org/0009-0004-7023-0298

---

## Research Papers & Reproducibility Index

This repository contains the manuscript sources and computational materials associated with **six research works**.

For each paper, direct links are provided to the publication record, PDF, LaTeX source, and associated computational or supplementary package.

---

### 1. A Ternary (4k±1)/3 Collatz-Type Map — Computational Study

This research studies the ternary Collatz-type map based on the residue-dependent transformations `(4k−1)/3` and `(4k+1)/3`.

The two Zenodo identifiers below belong to the same underlying research work and are therefore grouped here as a single research entry.

**Zenodo**

* https://doi.org/10.5281/zenodo.22195651
* https://doi.org/10.5281/zenodo.22195652

**Repository files**

* [PDF](Ternary_4k_pm_1_over_3_Collatz_Map.pdf)
* [LaTeX source](Ternary_4k_pm_1_over_3_Collatz_Map.tex)
* [Data and computational code](Ternary_4k_pm_1_over_3_Collatz_Map_Data_and_Code.zip)

---

### 2. A Ternary (4k±1)/3 Collatz-Type Map and Its (4n±4^r)/3 Scaled Family

This work develops a scaled family associated with the ternary `(4k±1)/3` system and studies its powers-of-4 scaling structure.

**Related base DOI**

* https://doi.org/10.5281/zenodo.22195651
* https://doi.org/10.5281/zenodo.22195652
 
**Zenodo DOI**

* https://doi.org/10.5281/zenodo.22228200

**Repository files**

* [PDF](Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family.pdf)
* [LaTeX source](Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_General.tex)
* [Complete research and computational package](Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_FINAL.zip)

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

* [PDF](A_Ternary_4k1_2_over_3_Collatz_Type_Map.pdf)
* [LaTeX source](A_Ternary_4k1_2_over_3_Collatz_Type_Map.tex)
* [Supplementary computational package](A_Ternary_4k1_2_over_3_Collatz_Type_Map_Supplementary.zip)

---

### 4. A Ternary (4k+1(2))/3 Collatz-Type Map and Its 4^r-Scaled Family

This work develops the `4^r`-scaled family associated with the preceding `(4k+1(2))/3` compressed ternary system.

**Zenodo record**

* https://zenodo.org/records/22639385

**Related base DOI**

* https://doi.org/10.5281/zenodo.22279137

**Repository files**

* [PDF](A_Ternary_4k1_2_over_3_Scaled_Family.pdf)
* [LaTeX source](A_Ternary_4k1_2_over_3_Scaled_Family.tex)
* [Complete research package](A_Ternary_4k1_2_over_3_Scaled_Family.zip)

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

* [PDF](A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9.pdf)
* [LaTeX source](A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9.tex)
* [Complete computational package](A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9_COMPLETE.zip)

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

* [PDF](A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3.pdf)
* [LaTeX source](A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3.tex)
* [Complete reproducibility package](A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3_COMPLETE.zip)

---

## Research Structure

The six works belong to **three distinct research lines**.

They use related ternary and 3-adic ideas, but they should not be treated as a single dynamical system.

### I. Ternary (4k±1)/3 line

1. Base computational research — Zenodo `22195651 / 22195652`
2. Scaled-family research — Zenodo `22228200`

### II. Ternary (4k+1(2))/3 line

3. Base compressed map with two observed attracting cycles — Zenodo `22279137`
4. Its `4^r`-scaled family — Zenodo record `22639385`

### III. Ternary (4k−1(2))/3 line

5. Base accelerated map with three observed positive attractors — Zenodo `22662980`
6. Its exactly conjugate `4^r`-scaled family — Zenodo `22671949`

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

The computational implementation is not identical across all six publications.

Researchers should consult the specific manuscript and computational package associated with the paper being examined.

---

## Computational Scope

All exhaustive computational statements in these works refer to explicitly stated **finite ranges**.

Verification through `10^9`, `10^11`, or any other finite numerical bound does not by itself constitute a proof of global convergence for all positive integers.

Where a scaled-family result is obtained through exact algebraic conjugacy, the result represents an algebraic transfer from the corresponding base system and should not be interpreted as an independent exhaustive scan of every integer below the scaled numerical bound.

---

## Citation

When using a particular mathematical result, manuscript source, computational result, or reproducibility package from this repository, please cite the corresponding Zenodo publication listed in the **Research Papers & Reproducibility Index**.

See also:

* [CITATION.cff](CITATION.cff)

---

## Author & Contact

**Farhad Banazadeh**
Independent mathematics researcher

**ORCID:**
https://orcid.org/0009-0004-7023-0298

**GitHub:**
https://github.com/FarhadBanazadeh

---

## Copyright and Reuse

Copyright and reuse terms may differ between publications.

Researchers should consult the corresponding Zenodo record and manuscript for the rights statement applicable to a particular work.

For publications carrying the current all-rights-reserved statement:

**© 2026 Farhad Banazadeh. All rights reserved.**

The presence of source code, manuscripts, data, or supplementary material in this repository should not by itself be interpreted as granting reuse rights beyond those explicitly stated for the corresponding work.

---

## Persistent Publication Records

Zenodo provides the persistent publication records and DOI identifiers for the research works represented in this repository.

The repository serves as a structured source and reproducibility archive complementing those publication records.
