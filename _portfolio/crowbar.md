---
title: "Crowbar"
excerpt: "Crowbar is a deductive verification tool for ABS, based on heavyweight symbolical execution and behavioral contracts."
collection: portfolio
date: 2014-01-01
---

Crowbar is a deductive verification tool for ABS, based on heavyweight symbolical execution and behavioral contracts.
Behavioral contracts allow the modular verification of Active Objects by specifying each interaction point (method start, method termination, suspension, rescheduling, synchronization) seperatly. Failed proof attempts can be investigated using executable counter examples, where a failed proof branch is presented as a program whose execution violates the contract and can be used for debugging without exposing the user to the verification logic.

Crowbar covers full CoreABS. Documentation is available in the github [repository](https://github.com/Edkamb/crowbar-tool).
