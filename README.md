![GitHub last commit](https://img.shields.io/github/last-commit/ArmanMoradi001/MPCitH-Survey.git)
![GitHub Repo stars](https://img.shields.io/github/stars/ArmanMoradi001/MPCitH-Survey.git)
![GitHub License](https://img.shields.io/github/license/ArmanMoradi001/MPCitH-Survey.git)


# Head-in-the-MPC Survey

> A curated collection of papers, implementations, educational resources, and benchmarks related to the **Head-in-the-MPC (MPCitH)** paradigm.

This repository accompanies our survey paper on the **Head-in-the-MPC (MPCitH)** paradigm and aims to provide researchers, engineers, and practitioners with a centralized collection of high-quality resources.

---

## Motivation

Zero-Knowledge Proofs (ZKPs) have become one of the most important building blocks of modern privacy-preserving systems.

Among different approaches, **Head-in-the-MPC (MPCitH)** has emerged as one of the most promising paradigms because it offers

- Transparent setup
- Post-quantum security
- Standard symmetric cryptographic assumptions
- Efficient signature constructions
- Applications in digital identity, CBDC, blockchain, and privacy-preserving finance

Despite its growing importance, educational resources remain scattered across papers, GitHub repositories, and technical blogs.

This repository tries to solve that problem.

---

# Repository Structure

```

.

├── implementations/
│
├── papers/
│ ├── bibliography.bib
│ └── references.md
│
├── resources/
│ ├── books.md
│ ├── tutorials.md
│ └── videos.md
│
└── README.md

```

---

# Contents

- Research Papers
- Official Implementations
- Books
- Tutorials
- Videos
- Benchmarks
- Learning Resources

---

# What is Head-in-the-MPC?

Head-in-the-MPC (MPCitH) is a Zero-Knowledge paradigm introduced by Ishai et al. (STOC 2007).

Instead of executing a real secure multi-party computation among several parties, the prover simulates multiple virtual parties locally.

Using commitments and challenge-response techniques, the verifier becomes convinced that the computation was performed correctly without learning the witness.

Major advantages include:

- No Trusted Setup
- Post-Quantum Security
- Standard Symmetric Assumptions
- Relatively Simple Cryptographic Building Blocks

---

# Major Protocols

| Protocol | Year | Main Contribution |
|----------|------|------------------|
| IKOS | 2007 | Original MPCitH Paradigm |
| ZKBoo | 2016 | First Practical Construction |
| ZKBoo++ | 2017 | Reduced Communication |
| Ligero | 2017 | Sublinear Proof Size |
| KKW | 2018 | Improved NIZK Construction |
| Limbo | 2021 | Efficient Proof System |
| Banquet | 2021 | Short Post-Quantum Signatures |

---

# Applications

- Digital Signatures
- Zero-Knowledge Authentication
- Central Bank Digital Currency (CBDC)
- Privacy-preserving KYC
- Anti-Money Laundering (AML)
- Blockchain
- Smart Contracts
- Threshold Signatures
- MPC Wallets
- Secure Data Sharing

---

# Repository Contents

## Papers

A curated reading list ordered from foundational papers to modern developments.

See:

```

papers/references.md

```

---

## Bibliography

Ready-to-use BibTeX entries.

```

papers/bibliography.bib

```

---

## Implementations

Official implementations collected from their original authors.

Examples include

- Picnic
- FAEST
- MP-SPDZ
- EMP Toolkit
- LowMC

---

## Books

Recommended books for learning

- Secure Multi-Party Computation
- Zero Knowledge
- Modern Cryptography

---

## Tutorials

Learning resources for beginners and advanced readers.

---

## Videos

Conference talks, lectures, tutorials, and presentations.

---

# Recommended Learning Path

For beginners:

1. Yao's Secure Computation
2. Secret Sharing
3. Secure MPC
4. Zero Knowledge
5. MPC-in-the-Head
6. ZKBoo
7. Ligero
8. Picnic
9. Banquet

---

# Companion to the Survey Paper

This repository accompanies the survey paper

**Head-in-the-MPC: Foundations, Evolution, and Applications in Privacy-Preserving Financial Systems**

The repository provides additional materials that cannot be included in the paper because of page limitations.

---

# Contributing

Contributions are welcome.

Feel free to submit

- new papers
- implementations
- tutorials
- benchmark results
- educational materials

using Pull Requests.

---

# Citation

If you find this repository useful, please cite our survey paper.

BibTeX is available in

```

papers/bibliography.bib

```

---

# License

Unless otherwise stated, this repository only contains metadata, educational material, and links to official implementations.

All copyrights remain with the original authors.

---

# Acknowledgements

We thank the cryptographic research community, especially the authors of

- IKOS
- ZKBoo
- Ligero
- Picnic
- Banquet
- FAEST

for making their research publicly available.

---

# Disclaimer

This repository is intended for educational and research purposes.

Links point to official implementations whenever possible.

The maintainers do not claim ownership of third-party projects.