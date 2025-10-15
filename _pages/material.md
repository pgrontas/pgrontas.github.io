---
layout: archive
title: "Cryptography Material"
permalink: /material/
author_profile: true
---

Below you can find material from the courses I co-taught in the NTUA, ALMA [undergraduate](https://courses.corelab.ntua.gr/crypto/) and [postgraduate](https://courses.corelab.ntua.gr/atc/) course.

Most of the slides are in Greek. Some of them have been based on previous lectures by Prof. Aris Pagourtzis and Prof. Stathis Zachos. 

## Cryptography

### Formal Models and Diffie-Hellman Key Exchange

Modern cryptography can be summarized as Formal Models + Security Proofs. In this lecture, we summarize the evolution of the security models for various cryptographic tasks and use the Diffie - Hellman key exchange protocol in order to demonstrate a first security proof. [Slides](/files/teaching/cryptoFormalModels.pdf)

### Factoring and RSA

This lecture outlines the RSA cryptosystems and its mathematical foundations. We also cover the various attacks that have been mounted on this cryptosystem during its history and analyze the lesson learnt from them. We also cover its secure variations and prove their security.  [Slides](/files/teaching/cryptoFormalModels.pdf)

### Cryptosystems based on the discrete logarithm problem

We outline the discrete logarithm problem (DLP) and its variations. We present algorithms to solve it and their effect on key sizes. We also define the DLP problem on elliptic curves. Then we present cryptographic constructions that reduce to DLP variations such as the ElGamal cryptosystem, and analyze their security. We conclude with a discussion on commitment schemes and secret sharing. [Slides](/files/teaching/DLP.pdf)

### Zero-Knowledge Proofs

This is the topic that fascinated me so much that I got into cryptography! Can a person be convinced only about the truth of a statement, without learning anything else! Surprisingly, for all statements of interest (call me NP) the answer is a yes! We present the concept of Zero-Knowledge (ZK)proofs from a computational complexity standpoint and then we discuss their applications in cryptography, beginning from the Schorr protocol, the Chaum-Pedersen protocol and Σ-protocols in general. [Slides](/files/teaching/ZK_ppt.pdf)

#### ZK-SNARKS

ZK-SNARKS are ZK-Proofs where the proof size is short and verification is fast. We discuss polynomial commitments, the KZG scheme, Bulletproofs, the Sumcheck protocol, and a bit of PLONK. [Slides](/files/teaching/zkSNARKs.pdf).

### Digital Signatures

A fundamental cryptographic primitive that allows authentication, pubic verifiability and non-repudiation. We formalize their security and provide construction based on RSA, ElGamal, ECDSA, Schnorr. We also discuss about key distribution and PKI. [Slides](/files/teaching/DS_ppt.pdf)

#### Blind Signatures

Blind signatures turn digital signatures from single party to interactive protocols, where th signer cannot have access to the message and cannot link signature generation with signature verification. We present formal models, constructions and application. [Slides](/files/teaching/blind.pdf).

#### Ring Signatures

Ring signatures allow the signer of a message to be hidden among a group of peers selected ad hoc. [Slides](/files/teaching/ring.pdf)

#### Advanced topics

We discuss signatures from identification schemes and how to prove the security of Schnorr signatures. [Slides](/files/teaching/secDsBs.pdf)

### Electronic Voting With Cryptography

The topic of my PhD thesis, in a mega-lesson, parts of which I use both on the undergraduate and postgraduate courses.
Cryptography in voting aims to resolve the impossible dilemma: Can we have public verifiability of an election, while keeping the ballots secret? Paradoxically, the answer is yes! (under assumptions of course). This lecture, describes the solutions, their limitations and the most widely used formal models that are used to reason about them. [Slides](/files/teaching/cryptovoting.pdf).

All material in this page is provided under license CC BY-NC-SA.

 ![CC BY-NC-SA](/images/by-nc-sa.png)
