+++
title = "Intrusion tolerance as a service"
type = "page"
layout = "single"
weight = 2
summary = "We are developing new techniques to make intrusion-tolerant systems easier to deploy by offloading part of the system management to a cloud service provider."
+++

Intrusion tolerance, or the ability to operate correctly even
while partially compromised by an attacker, is an increasingly
important concern for high value systems.
However, despite a long line of work on using Byzantine Fault Tolerant (BFT)
replication to enable such high value systems to withstand successful
intrusions, such solutions are still challenging to deploy in practice and
require a high level of expertise to manage.

Further complicating deployment, we have shown that tolerating sophisticated
*network attacks* in addition to intrusions requires that system management and
state be distributed across at least three distinct geographic sites (see
["Network-Attack-Resilient Intrusion-Tolerant SCADA for the Power
Grid"](http://www.dsn.jhu.edu/papers/scada_DSN_2018.pdf)).

We are developing new techniques to make intrusion-tolerant systems easier to
deploy by offloading part of the system management to a cloud service provider.
However, this raises significant *confidentiality* concerns, as sharing
sensitive data and/or proprietary algorithms with a cloud provider may not be
an acceptable trade-off.

Our recent work, ["Toward Intrusion Tolerance as a Service: Confidentiality in
Partially Cloud-Based BFT
Systems"](https://sites.pitt.edu/~babay/pubs/dsn21_confidentialBFT.pdf),
published in [DSN 2021](https://dsn2021.ntu.edu.tw/) has shown how we can make
use of cloud sites to host additional system replicas *without needing to
expose any unencrypted state* to the cloud.

We are continuing to work to develop new architectures to further simplify
system management and meet the needs of a broad range of applications.
