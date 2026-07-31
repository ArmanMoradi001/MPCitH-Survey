# Tutorials

This document collects high-quality tutorials, lecture notes, workshops, blog posts, and hands-on learning materials related to **Head-in-the-MPC (MPCitH)** and its prerequisites.

Unlike the research papers, these resources focus on learning the concepts rather than presenting new results.

---

# Learning Roadmap

If you are new to the field, follow this learning order:

1. Modern Cryptography
2. Secret Sharing
3. Secure Multi-Party Computation (MPC)
4. Zero-Knowledge Proofs
5. MPC-in-the-Head
6. Post-Quantum Cryptography
7. Industrial Applications

---

# Cryptography Fundamentals

## Stanford Cryptography I

**Instructor**

Dan Boneh

**Level**

Beginner

**Topics**

- Symmetric Encryption
- Public-Key Cryptography
- Digital Signatures
- Hash Functions
- Cryptographic Protocols

**Why Learn**

One of the best introductions to modern cryptography.

---

## Stanford Cryptography II

**Instructor**

Dan Boneh

**Level**

Intermediate

**Topics**

- Zero-Knowledge
- Secure Computation
- Advanced Cryptography

**Recommended Before Reading**

- ZKBoo
- Ligero
- Banquet

---

# Secret Sharing

## Shamir Secret Sharing Explained

**Level**

Beginner

**Topics**

- Polynomial Secret Sharing
- Threshold Schemes
- Reconstruction

**Why Learn**

Secret Sharing is one of the fundamental building blocks behind Secure MPC.

---

## Interactive Secret Sharing Demonstrations

Recommended topics:

- Lagrange Interpolation
- Threshold Reconstruction
- Share Distribution

---

# Secure Multi-Party Computation

## MP-SPDZ Documentation

Official documentation:

https://github.com/data61/MP-SPDZ

**Topics**

- Secure Computation
- Secret Sharing
- Arithmetic Circuits
- Boolean Circuits

---

## EMP Toolkit Documentation

Official documentation:

https://github.com/emp-toolkit

**Topics**

- Garbled Circuits
- Secure Two-Party Computation
- MPC

---

## Bristol Fashion Circuits

Official Repository:

https://github.com/mkskeller/bristol-fashion

**Topics**

- Boolean Circuits
- AES Circuits
- SHA Circuits

Useful for understanding practical MPC implementations.

---

# Zero-Knowledge Proofs

## Zero Knowledge Proofs Explained

Recommended topics:

- Interactive Proofs
- Fiat-Shamir Transform
- Commitments
- Proof Systems

---

## zkSNARK vs zkSTARK

Recommended topics:

- Trusted Setup
- Transparency
- Proof Size
- Verification Time

Understanding these concepts helps position MPCitH within the broader ZKP ecosystem.

---

# Head-in-the-MPC

## Original IKOS Paper

Read after learning:

- Secret Sharing
- MPC
- Zero-Knowledge

Key ideas:

- Virtual Parties
- Local Simulation
- Commitments
- Challenge Phase

---

## ZKBoo

Topics to focus on:

- Boolean Circuits
- MPC Simulation
- Three Virtual Parties
- Proof Compression

---

## ZKBoo++

Topics

- Communication Reduction
- Optimized Commitments

---

## Ligero

Topics

- Error Correcting Codes
- Linear Algebra
- Proof Compression

---

## Banquet

Topics

- AES-based Signatures
- MPCitH
- Post-Quantum Security

---

# LowMC

Before reading Picnic or Banquet, learn

- LowMC Design
- S-box Layer
- Linear Layer

Understanding LowMC significantly simplifies the Picnic paper.

---

# Post-Quantum Cryptography

## NIST Post-Quantum Cryptography Project

Official website

https://csrc.nist.gov/projects/post-quantum-cryptography

Recommended topics

- Digital Signatures
- Security Categories
- Standardization Process

---

## Picnic Signature

Official project

https://microsoft.github.io/Picnic/

Topics

- MPC-in-the-Head
- LowMC
- Fiat-Shamir
- Signature Generation

---

## FAEST

Recommended after Picnic.

Topics

- AES-based Signatures
- Efficient MPCitH
- Modern Optimizations

---

# Financial Applications

Recommended learning topics

- Privacy-Preserving KYC
- Secure AML
- Confidential Transactions
- CBDC Privacy
- Threshold Signatures
- MPC Wallets

---

# Hands-on Practice

After finishing the theoretical material, try implementing

- XOR Secret Sharing
- Shamir Secret Sharing
- Beaver Triples
- Simple MPC
- Fiat-Shamir Transform
- Toy Zero-Knowledge Proof
- Toy MPC-in-the-Head

Do **not** begin with Picnic.

Build intuition through small implementations first.

---

# Suggested Weekly Study Plan

| Week | Topic |
|-------|------------------------------|
| 1 | Cryptography Fundamentals |
| 2 | Secret Sharing |
| 3 | Secure MPC |
| 4 | Boolean Circuits |
| 5 | Zero-Knowledge Proofs |
| 6 | MPC-in-the-Head |
| 7 | ZKBoo |
| 8 | Ligero |
| 9 | Picnic |
| 10 | Banquet |
| 11 | Industrial Applications |
| 12 | Research Papers |

---

# Recommended Background

Before studying MPCitH, readers should be comfortable with

- Linear Algebra
- Probability
- Discrete Mathematics
- Complexity Theory
- Finite Fields
- Basic Cryptography

---

# Common Mistakes

Many newcomers jump directly into the Picnic or Banquet papers.

A much better progression is

Cryptography

↓

Secret Sharing

↓

Secure MPC

↓

Zero-Knowledge

↓

IKOS

↓

ZKBoo

↓

Ligero

↓

Picnic

↓

Banquet

This order dramatically reduces the learning curve.

---

# Additional Learning Resources

Useful places to explore:

- IACR ePrint Archive
- NIST Post-Quantum Cryptography Project
- Microsoft Research Cryptography
- MP-SPDZ Documentation
- EMP Toolkit Documentation
- Crypto Stack Exchange

---

# Contributing

If you know a high-quality tutorial, workshop, lecture, blog post, or educational resource related to MPCitH, feel free to submit a Pull Request.