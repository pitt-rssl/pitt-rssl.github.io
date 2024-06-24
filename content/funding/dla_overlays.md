+++
title = "Seamless Linux-Based Intrusion-Tolerant Networks"
type = "page"
layout = "single"
date = "2024-07-01"
publishdate = "2024-06-24"
summary = "This project investigates how to enable legacy applications to use intrusion-tolerant overlay networks. This enables resilient communication for such applications (ensuring messages are delivered in a timely manner, even when the network is under attack), without requiring any changes to the application."
funder = "Defense Logistics Agency (DLA)"
funder_link = "https://www.dla.mil/"
+++

### Team
- University of Pittsburgh
    - [Dr. Amy Babay](https://sites.pitt.edu/~babay/)
- Spread Concepts LLC
    - [Dr. Yair Amir](https://www.linkedin.com/in/yair-amir-61b58/)

### Overview

Today's military command and control and logistics applications require
collecting information from and coordinating among many distributed components
over IP networks. To ensure that these applications can continue to work, even
in the face of sophisticated cyberattacks, it is crucial to construct networks
that are resilient to the point of intrusion tolerance, meaning that they are
able to work even when part of the network is compromised.

Our prior research has developed techniques to deploy intrusion-tolerant
networks on top of existing IP network infrastructure using an [overlay
concept](https://sites.pitt.edu/~babay/pubs/icdcs2016_PITN.pdf).

This project addresses two gaps in deploying intrusion-tolerant networks to
support mission-critical military applications:
- Building support for legacy applications. We will develop an interceptor
  capability to funnel legacy application communication through the
  intrusion-tolerant overlay, without modifying the application.
- Creating a deployment stragegy and addressing concept. We will develop a
  strategy to enable intrusion-tolerant communication between components that
  need it, while not interfering with other existing communications.

### Demonstrations

- Demonstration of a file copy using the standard SCP program over an
  intrusion-tolerant network:
  [video](https://sites.pitt.edu/~babay/itn/2024_04_ITN_SCP_Demo.mp4)

- Demonstration of a real-time video transmission over an intrusion-tolerant
  network. The video traffic is sent from source to destination, and then
  reflected back to the source (also over the intrusion-tolerant network) to
  measure the round-trip delay:
  [video](https://sites.pitt.edu/~babay/itn/itn_realtime_demo.mp4)
