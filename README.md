# Sequence Computations

Research articles, LaTeX sources, computational packages, and reproducibility materials for ternary Collatz-type maps and their scaled families.

**Author:** Farhad Banazadeh  
**ORCID:** https://orcid.org/0009-0004-7023-0298

---

## Research Papers & Reproducibility Index

This repository contains the manuscript sources and computational materials associated with eight research works.
For each paper, direct links are provided to the publication record, PDF, LaTeX source, and associated computational or supplementary package.

---

### 1. A Ternary (4k±1)/3 Collatz-Type Map — Computational Study

This research studies the ternary Collatz-type map based on the residue-dependent transformations `(4k−1)/3` and `(4k+1)/3`.

The two Zenodo identifiers below belong to the same underlying research work and are therefore grouped here as a single research entry.

**Zenodo**

- https://doi.org/10.5281/zenodo.22195651
- https://doi.org/10.5281/zenodo.22195652

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map.tex)
- [Data and computational code](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map_Data_and_Code.zip)

---

### 2. A Ternary (4k±1)/3 Collatz-Type Map and Its (4n±4^r)/3 Scaled Family

This work develops a scaled family associated with the ternary `(4k±1)/3` system and studies its powers-of-4 scaling structure.

**Related base DOI**

- https://doi.org/10.5281/zenodo.22195651
- https://doi.org/10.5281/zenodo.22195652

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22228200

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_General.tex)
- [Complete research and computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_FINAL.zip)

---

### 3. A Ternary (4k+1(2))/3 Collatz-Type Map with Two Attracting Cycles

This is an independent compressed ternary Collatz-type system defined on positive integers not divisible by 3.

The finite exhaustive computation through `10^9` identifies two observed attracting cycles:

- `C1 = (1, 2)`
- `C7 = (7, 10, 14, 19, 26, 35, 47)`

The finite computation provides computational evidence and does not constitute a proof of global convergence.

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22279137

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map.tex)
- [Supplementary computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map_Supplementary.zip)

---

### 4. A Ternary (4k+1(2))/3 Collatz-Type Map and Its 4^r-Scaled Family

This work develops the `4^r`-scaled family associated with the preceding `(4k+1(2))/3` compressed ternary system.

**Zenodo record**

- https://zenodo.org/records/22639385

**Related base DOI**

- https://doi.org/10.5281/zenodo.22279137

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Scaled_Family.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Scaled_Family.tex)
- [Complete research package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Scaled_Family.zip)

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

- fixed point `1`
- fixed point `2`
- four-cycle `22 → 29 → 38 → 50 → 22`

No unresolved or overflowing trajectory was found in the tested range.

This is finite computational evidence and is not a proof of global convergence for all positive integers.

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22662980

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9.tex)
- [Complete computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k_minus_1_2_over_3_Collatz_Map_10e9_COMPLETE.zip)

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

- https://doi.org/10.5281/zenodo.22662980

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22671949

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3.tex)
- [Complete reproducibility package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_4r_Scaled_Family_Ternary_4k_minus_1_2_over_3_COMPLETE.zip)

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

- tested: `99,000,000,000`
- certified: `99,000,000,000`
- unsigned 128-bit overflows: `0`
- maximum steps to the verified base interval: `548`
- corresponding start: `58,528,894,046`
- largest encountered value: `1,030,251,791,629,144,029,921`
- corresponding start: `72,496,238,260`
- peak iteration: `168`

An earlier unsigned 64-bit computation left 158 starts unresolved solely because intermediate orbit values exceeded the 64-bit range. The complete 128-bit rescan eliminated this arithmetic limitation and produced zero overflows.

Combining this certification with the previous exhaustive verification through `10^9` establishes that every starting value

`1 ≤ n ≤ 10^11`

has been computationally verified to reach `1` under this map.

This is a finite exhaustive computational verification and does not constitute a proof of global convergence for all positive integers.

**Related base research**

- https://doi.org/10.5281/zenodo.22195651
- https://doi.org/10.5281/zenodo.22195652

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22685074

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Extended_Computational_Verification_Ternary_4k_pm_1_over_3_1e11.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Extended_Computational_Verification_Ternary_4k_pm_1_over_3_1e11.tex)
- [Complete reproducibility package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Extended_Computational_Verification_Ternary_4k_pm_1_over_3_1e11_COMPLETE.zip)

---

### 8. Ternary (5k±1)/4 Collatz-Type Map with Two Observed Attractors: Exhaustive Computational Verification up to 10^10 and Algebraic Structure

This work studies the ternary `(5k±1)/4` Collatz-type map on positive odd integers.

The dynamical system exhibits two observed attractors:

- fixed point `1`
- three-cycle `13 → 33 → 83 → 13`

An exhaustive finite computation was performed for all positive odd starting values below `10^10`.

Every tested starting value entered one of the two observed attractors, and no additional terminal cycle was detected in the verified range.

This is finite exhaustive computational evidence and does not constitute a proof of global convergence for all positive odd integers.

**Zenodo DOI**

- https://doi.org/10.5281/zenodo.22709065

**Repository files**

- [PDF](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10.pdf)
- [LaTeX source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10.tex)
- [Computational package](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Farhad_Banazadeh_Zenodo22709065_Ternary_5k_pm_1_over_4_Collatz_Type_Map_up_to_1e10_Computational_Pack.zip)
---

## Research Structure

The eight works belong to **three distinct research lines**.

They use related ternary and 3-adic ideas, but they should not be treated as a single dynamical system.

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

8. Ternary (5k±1)/4 Collatz-type map with two observed attractors — Zenodo `22709065
 
---

## How to Find the Source of a Paper

Researchers should use the **Research Papers & Reproducibility Index** above rather than identify files from filenames alone.

Each research entry provides direct access to:

- the corresponding Zenodo publication or record;
- the compiled PDF;
- the exact LaTeX manuscript source;
- the associated computational or supplementary package.

This structure is intended to make the provenance of every manuscript and computational package immediately identifiable.

---

## Reproducibility Materials

Depending on the publication, this repository contains:

- LaTeX manuscript sources (`.tex`)
- compiled research papers (`.pdf`)
- C source code
- Python verification scripts
- computational summaries
- JSON data
- trajectory and verification outputs
- supplementary archives
- reproducibility ZIP packages
- checksum files

The computational implementation is not identical across all seven publications.

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

- [CITATION.cff](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/CITATION.cff)

---

## Author & Contact

**Farhad Banazadeh**  
Independent mathematics researcher

**ORCID:** https://orcid.org/0009-0004-7023-0298

**GitHub:** https://github.com/FarhadBanazadeh

---

## Copyright and Reuse

Copyright © 2026 Farhad Banazadeh.

All seven research publications represented in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

Under CC BY 4.0, the publications may be shared and adapted for any purpose, including commercial use, provided that appropriate credit is given to the author, a link to the license is provided, and any changes made are indicated.

**Author:** Farhad Banazadeh  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

For the authoritative publication metadata and licensing information for each work, please consult its corresponding Zenodo record.
---

## Persistent Publication Records

Zenodo provides the persistent publication records and DOI identifiers for the research works represented in this repository.

The repository serves as a structured source and reproducibility archive complementing those publication records.
