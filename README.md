# Lattice-based Functional Commitment

This PoC implements a lattice-based functional commitment scheme describe in [WW23](https://eprint.iacr.org/2024/028) for constant-degree polynomials, focusing on fast verification and leveraging the security of the ℓ-succinct SIS assumption.

## Components Overview

- [ ] Utils
    - [ ] Lattice Utilities: Provides basic matrix arithmetic and basis reduction algorithms
    - [ ] Discrete Gaussian Sampling: Implements discrete Gaussian sampling over integers and lattices
- [ ] Parameters Setup
    - [ ] Generates global parameters
    - [ ] Generates the CRS, including matrices based on the ℓ-succinct SIS assumption
- [ ] Trapdoor
    - [ ] enabling efficient preimage sampling
    - [ ] ready to be used in commitment and opening phases
- [ ] Commitment and Opening
    - [ ] Can commit to a constant-degree polynomial
    - [ ] Generates an opening proof for a committed polynomial at a specific evaluation point
- [ ] Verification
    - [ ] Basic verification
    - [ ] Support for preprocess function
