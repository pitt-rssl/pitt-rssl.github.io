+++
title = "Mobile Control Center Support for Intrusion-Tolerant SCADA"
type = "page"
layout = "single"
date = "2025-07-01"
publishdate = "2024-11-01"
summary = "This project investigates how to integrate a mobile control center into an intrusion-tolerant power grid SCADA system. This can enable power grid SCADA to better withstand compound threats involving natural hazards and cyberattacks."
funder = "Defense Logistics Agency (DLA)"
funder_link = "https://www.dla.mil/"
+++

### Team
- University of Pittsburgh
    - [Dr. Amy Babay](https://sites.pitt.edu/~babay/)
    - Jack Drabenstadt
    - Derrick Hicks
- Spread Concepts LLC
    - [Dr. Yair Amir](https://www.linkedin.com/in/yair-amir-61b58/)

### Overview

Compound threats, in which cyberattacks compound the damage caused by natural
hazards are an increasing concern for critical infrastructure, with an emerging
trend of sophisticated cyberattacks targeting infrastructure that is already
damaged or stressed by natural threats.

Our [recent
research](https://sites.pitt.edu/~babay/pubs/srds24_compoundThreats.pdf) has
shown that no existing power grid Supervisory Control and Data Acquisition
(SCADA) system architectures can adequately withstand compound threats. This
includes fault-tolerant architectures commonly deployed in industry, as well as
state-of-the-art intrusion-tolerant architectures designed to withstand
cyberattacks. Natural hazards may simultaneously make large parts of the
infrastructure unavailable, making it infeasible for any static system
architecture to withstand these threats.

There is an opportunity to improve resilience by integrating a mobile control
center that can be deployed in the aftermath of a natural hazard. If existing
control centers are rendered inoperable by a natural hazard (e.g. flooded by a
hurricane), a mobile control center may be deployed to resume operations.
However, protocols and software support for integrating a mobile control center
into a SCADA system are missing today.

This project addresses the following key gap in integrating a mobile control
center for improved resilience of power grid SCADA:
-	Designing, implementing, and demonstrating a reconfiguration protocol to
    integrate a mobile control center. Our past work developed a
    reconfiguration capability that can improve resilience in specific
    scenarios by excluding parts of the system to reduce the attack surface.
    However, this approach requires specifying the maximal topology of system
    components in advance. In this SOW, we will develop a reconfiguration
    capability that can integrate a mobile control center after the system is
    damaged by natural hazards and/or cyberattacks.
