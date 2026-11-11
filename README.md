# The T-map contracts at √3/2: a Collatz census below 10^6, a length-16 parity-vector bijection, and a coral inverse tree

**Author:** Benjamin Stanley Frohman  
**ORCID:** [0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718)  
**Date:** 18 September 2026  
**Location:** Lewisville, Texas

## Abstract

The accelerated Collatz map is defined by

\[ T(n) = \begin{cases} n/2 & \text{if } n \text{ even}, \\ (3n+1)/2 & \text{if } n \text{ odd}. \end{cases} \]

Its coin-flip geometric mean is \(\sqrt{1/2 \cdot 3/2} = \sqrt{3}/2 \approx 0.866025\). A complete census of all starting values below \(10^6\) yields a measured mean of 0.865312 (relative error \(8 \times 10^{-4}\)). Every orbit terminates at 1. The length-16 parity-vector bijection and a coral fragment of the inverse tree are exhibited. The delay record 837799 requires 524 steps.

This is a computational census and structural observation, not a proof of the Collatz conjecture.

## Files

- `Frohman_Collatz_Census_2026.pdf` (to be uploaded on Zenodo)
- `.zenodo.json` — machine-readable metadata for automatic Zenodo deposit via GitHub integration
- `CITATION.cff` — citation metadata

## Zenodo Deposit Instructions

1. Connect this repository to Zenodo under [Zenodo GitHub settings](https://zenodo.org/account/settings/github/).
2. Create a release (or tag) on this repository.
3. Zenodo will automatically open an unpublished draft deposit and reserve a DOI.
4. Upload the PDF in the Zenodo draft interface and publish when ready.

**Do not publish until the PDF is attached and metadata is reviewed.**

## License and copyright

Licensed under the Apache License, Version 2.0. See [`LICENSE`](LICENSE) and [`NOTICE`](NOTICE).

© 2026 Benjamin Stanley Frohman.
