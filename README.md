# Anonymous UC security proof for PCMCP

This repository provides supplementary UC security proof for the paper
“PCMCP: A Secure Privacy-Preserving Cross Multi-Party Channel Payment Scheme for Payment Channel Networks”.

The materials are provided to ensure the completeness of the UC framework presented in the paper and to allow reviewers to verify the correctness of the security arguments.

## Contents

- **Full_UC_security_proof.pdf**

  A self-contained document that includes:
  - the full ledger functionality for PCMCP (\(\mathcal{L}_{CMC}\));
  - the full case-by-case simulator for PCMCP (\(\mathcal{S}_{CMC}\));
  - a mapping between the simulator and the security proof in the main paper;
  - notes on leakage, assumptions, and UC composability.

## Relation to the Main Paper

Due to space constraints, only simplified ideal functionalities (\(\mathcal{F}_{CMC}\) and \(\mathcal{F}_{WT}\)) and a compact proof sketch are included in the main paper.

All artifacts in this repository are designed to realize exactly the functionalities defined in the main paper.
No additional security assumptions or protocol features are introduced here.

## Anonymity Statement

This repository is fully anonymized and contains no identifying information about the authors or their affiliations.
The content is provided solely for the purpose of anonymous peer review.

## Notes

All descriptions follow the Universal Composability (UC) framework.
The notation and terminology are consistent with those used in the main paper.
