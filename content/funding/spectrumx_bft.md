+++
title = "Byzantine Fault Tolerance in Spectrum Sharing Regimes"
type = "page"
layout = "single"
date = "2025-02-01"
publishdate = "2024-02-01"
summary = "This project investigates how to design a decentralized spectrum sharing system that can tolerate failures and malicious behavior from servers and sensors."
funder = "NSF SpectrumX"
funder_link = "https://www.spectrumx.org/"
+++

### Team
- University of Pittsburgh
    - [Dr. Amy Babay](https://sites.pitt.edu/~babay/)
    - [Dr. Prashant Krishnamurthy](https://sites.pitt.edu/~prashk/)

### Overview

We expect future dynamic spectrum sharing regimes to be implemented in a
distributed manner, to support efficient coordination among relevant entities
sharing spectrum slices. However, distributed coordination of spectrum
allocation is challenging, particularly in an environment where nodes may be
deployed by different (potentially competing) entities, may have differing
observations of physical properties such as interference levels, and may
experience failures (including node crashes, measurement errors, message loss,
or even security breaches leading to node compromises). The Byzantine fault
model provides a promising approach to reason about such challenges: in this
model, a fraction of nodes may behave in arbitrary or even malicious ways.
Byzantine Fault Tolerant (BFT) protocols enable correct nodes to make
consistent decisions despite arbitrary behavior from a subset of nodes.

In this seed project, we map spectrum sharing strategies to BFT models that can
make spectrum sharing trustworthy for incumbents and secondary users.
