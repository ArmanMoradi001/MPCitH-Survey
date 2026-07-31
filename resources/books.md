# Books

This document curates the most valuable books for learning the cryptographic foundations behind the **MPC-in-the-Head (MPCitH)** paradigm.

Rather than listing every cryptography book, this guide focuses on resources that directly help readers understand Secure Multi-Party Computation (MPC), Zero-Knowledge Proofs (ZKP), secret sharing, post-quantum cryptography, and privacy-preserving systems.

---

# Recommended Reading Order

| Level | Topic |
|---------|-------------------------------|
| Beginner | Modern Cryptography |
| Beginner | Secret Sharing |
| Intermediate | Secure Multi-Party Computation |
| Intermediate | Zero-Knowledge Proofs |
| Advanced | Cryptographic Proof Techniques |
| Advanced | Post-Quantum Cryptography |

---

# Essential Books

## 1. Foundations of Cryptography – Volume 2

**Author**

Oded Goldreich

**Publisher**

Cambridge University Press

**Year**

2004

**Topics**

- Secure Computation
- Zero-Knowledge
- Computational Security
- Interactive Proofs

**Why Read**

This is one of the most influential books in theoretical cryptography and provides the mathematical foundations required to understand Zero-Knowledge Proofs and MPC.

**Recommended Chapters**

- Secure Computation
- Zero-Knowledge
- Proof Systems

**Difficulty**

⭐⭐⭐⭐⭐

---

## 2. Secure Multiparty Computation and Secret Sharing

**Authors**

Ronald Cramer

Ivan Damgård

Jesper Buus Nielsen

**Publisher**

Cambridge University Press

**Year**

2015

**Topics**

- Secret Sharing
- MPC
- Security Models
- Honest Majority
- Malicious Security

**Why Read**

The definitive reference for Secure Multi-Party Computation.

Most concepts required for understanding MPC-in-the-Head originate from this book.

**Recommended Chapters**

- Secret Sharing
- Secure Computation
- Security Definitions

**Difficulty**

⭐⭐⭐⭐☆

---

## 3. Introduction to Modern Cryptography

**Authors**

Jonathan Katz

Yehuda Lindell

**Publisher**

CRC Press

**Year**

Third Edition

**Topics**

- Symmetric Cryptography
- Public-Key Cryptography
- Hash Functions
- Digital Signatures
- Zero-Knowledge

**Why Read**

Probably the best modern cryptography textbook for graduate students.

Highly recommended before studying MPCitH papers.

**Difficulty**

⭐⭐⭐☆☆

---

## 4. Understanding Cryptography

**Authors**

Christof Paar

Jan Pelzl

**Publisher**

Springer

**Year**

2010

**Topics**

- AES
- Hash Functions
- Block Ciphers
- Digital Signatures

**Why Read**

Excellent practical introduction.

Useful for understanding LowMC, AES-based signatures, and symmetric cryptography used in MPCitH.

**Difficulty**

⭐⭐☆☆☆

---

## 5. Real World Cryptography

**Author**

David Wong

**Publisher**

Manning

**Year**

2021

**Topics**

- Modern Cryptography
- Secure Protocols
- TLS
- Blockchain
- Cryptographic Engineering

**Why Read**

Explains how cryptographic primitives are deployed in real systems.

Helpful for engineers and practitioners.

**Difficulty**

⭐⭐☆☆☆

---

## 6. Handbook of Applied Cryptography

**Authors**

Alfred Menezes

Paul van Oorschot

Scott Vanstone

**Publisher**

CRC Press

**Year**

1996

**Topics**

- Cryptographic Algorithms
- Hash Functions
- Number Theory
- Signatures

**Why Read**

A classical reference book.

Still useful for understanding many primitives used in Zero-Knowledge systems.

**Difficulty**

⭐⭐⭐⭐☆

---

## 7. Serious Cryptography

**Author**

Jean-Philippe Aumasson

**Publisher**

No Starch Press

**Year**

2017

**Topics**

- Modern Cryptography
- Security Engineering
- Cryptographic Design

**Why Read**

A practical and highly readable book for software engineers.

Recommended before implementing cryptographic systems.

**Difficulty**

⭐⭐☆☆☆

---

# Books Specifically Relevant to MPCitH

Although no book is exclusively dedicated to **MPC-in-the-Head**, the following books provide nearly all prerequisite knowledge.

| Topic | Recommended Book |
|---------|------------------------------|
| Secret Sharing | Secure Multiparty Computation and Secret Sharing |
| Zero-Knowledge | Foundations of Cryptography |
| MPC | Secure Multiparty Computation and Secret Sharing |
| Symmetric Cryptography | Understanding Cryptography |
| Practical Cryptography | Real World Cryptography |
| Cryptographic Engineering | Serious Cryptography |

---

# Reading Path

If your goal is to understand MPCitH from scratch, follow this order:

1. Understanding Cryptography
2. Introduction to Modern Cryptography
3. Serious Cryptography
4. Foundations of Cryptography (Volume 2)
5. Secure Multiparty Computation and Secret Sharing
6. Research papers (IKOS, ZKBoo, Ligero, Banquet)

---

# Books for Different Audiences

## Students

- Understanding Cryptography
- Introduction to Modern Cryptography

---

## Researchers

- Foundations of Cryptography
- Secure Multiparty Computation and Secret Sharing

---

## Engineers

- Real World Cryptography
- Serious Cryptography

---

## Financial Technology Professionals

- Real World Cryptography
- Serious Cryptography
- Introduction to Modern Cryptography

---

# Free Resources

Some books or earlier editions may be legally available from the authors' webpages.

Whenever possible, prefer obtaining books from the publisher or official author websites.

---

# Missing Book?

Feel free to open a Pull Request if you know a book that significantly contributes to the MPC, Zero-Knowledge, or Post-Quantum Cryptography ecosystem.