# Research Papers

This document provides a curated reading roadmap for researchers, engineers, and practitioners interested in the **Head-in-the-MPC (MPCitH)** paradigm.

The papers are organized from foundational works to practical implementations and industrial applications.

---

# Reading Roadmap

| Stage | Topic |
|------|------|
| 1 | Foundations of Secure Computation |
| 2 | Secret Sharing |
| 3 | Zero-Knowledge Proofs |
| 4 | Head-in-the-MPC |
| 5 | Practical MPCitH Protocols |
| 6 | Post-Quantum Signatures |
| 7 | Industrial Applications |

---

# Stage 1 — Foundations of Secure Computation

## 1. Protocols for Secure Computations

**Andrew C. Yao**

FOCS 1982

**Why read**

The paper that introduced secure computation and laid the foundation for modern Secure Multi-Party Computation.

**Difficulty**

⭐⭐⭐☆☆

---

## 2. How to Play Any Mental Game

**Goldreich, Micali, Wigderson**

STOC 1987

**Why read**

Introduces the general MPC model that later became the basis for MPC-in-the-Head.

**Difficulty**

⭐⭐⭐⭐☆

---

## 3. Foundations of Cryptography (Volume 2)

**Oded Goldreich**

Cambridge University Press

**Why read**

Comprehensive theoretical background for secure computation and cryptographic proofs.

**Difficulty**

⭐⭐⭐⭐☆

---

# Stage 2 — Secret Sharing

## 4. How to Share a Secret

**Adi Shamir**

Communications of the ACM

1979

**Why read**

Introduces Shamir Secret Sharing, one of the core primitives used throughout MPC.

**Difficulty**

⭐⭐☆☆☆

---

## 5. Secure Multiparty Computation and Secret Sharing

**Cramer, Damgård, Nielsen**

Cambridge University Press

2015

**Why read**

One of the best books on practical MPC.

**Difficulty**

⭐⭐⭐⭐☆

---

# Stage 3 — Zero-Knowledge Proofs

## 6. The Knowledge Complexity of Interactive Proof Systems

**Goldwasser, Micali, Rackoff**

1989

**Why read**

Introduces Zero-Knowledge Proofs.

**Difficulty**

⭐⭐⭐⭐☆

---

## 7. Efficient Zero-Knowledge Proofs and Arguments

**Joe Kilian**

STOC 1992

**Why read**

Classic paper on efficient zero-knowledge constructions.

**Difficulty**

⭐⭐⭐⭐☆

---

# Stage 4 — Head-in-the-MPC

## 8. Zero-Knowledge from Secure Multiparty Computation

**Ishai, Kushilevitz, Ostrovsky, Sahai**

STOC 2007

**Why read**

The original MPC-in-the-Head paper.

Every researcher entering this field should read this paper first.

**Difficulty**

⭐⭐⭐⭐⭐

---

# Stage 5 — Practical MPCitH Protocols

## 9. ZKBoo

USENIX Security 2016

**Contribution**

First practical MPCitH protocol.

**Keywords**

Boolean Circuits

Proof Compression

---

## 10. ZKBoo++

CCS 2017

**Contribution**

Reduced communication complexity.

---

## 11. Ligero

CCS 2017

**Contribution**

Sublinear proof size.

---

## 12. KKW

2018

**Contribution**

Improved non-interactive ZK.

---

## 13. Limbo

CCS 2021

**Contribution**

Efficient MPCitH-based arguments.

---

## 14. Banquet

2021

**Contribution**

Short post-quantum signatures based on AES.

---

# Stage 6 — Post-Quantum Cryptography

## 15. Picnic Digital Signature

NIST PQC

**Why read**

One of the most important real-world applications of MPCitH.

---

## 16. FAEST

**Why read**

Modern post-quantum signature scheme based on MPCitH ideas.

---

# Stage 7 — Industrial Applications

## 17. MP-SPDZ

Official MPC Framework

https://github.com/data61/MP-SPDZ

**Purpose**

Research and production-quality MPC framework.

---

## 18. Fireblocks

https://www.fireblocks.com/

**Purpose**

Commercial MPC wallet infrastructure.

---

## 19. Sharemind

https://sharemind.cyber.ee/

**Purpose**

Privacy-preserving analytics platform.

---

## 20. Roseman Labs

https://rosemanlabs.com/

**Purpose**

Privacy-preserving collaborative analytics.

---

# Suggested Reading Order

If you are completely new to the area, follow this sequence:

1. Yao (1982)
2. GMW (1987)
3. Shamir Secret Sharing
4. Goldwasser–Micali–Rackoff
5. IKOS (2007)
6. ZKBoo
7. Ligero
8. Picnic
9. Banquet

---

# Citation

The complete BibTeX entries for all papers are available in

```
papers/bibliography.bib
```