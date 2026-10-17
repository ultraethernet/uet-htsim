# uec-transport-simulation-code

> This is a fork of the official repository,
> [ultraethernet/uet-htsim](https://github.com/ultraethernet/uet-htsim).

This repository is dedicated to the Congestion Management Group.

By contributing to this project you agree to the Developer's
Certificate of Origin 1.1 (at http://developercertificate.org) for the
contribution, and to license your contribution under the terms
specified in the LICENSE-Transport-WG.txt file (the BSD 2-Clause
License).

Please note that we only accept contributions from UEC members at this time.

# Purpose and Scope

HTSIM is a high-performance discrete event simulator used for network simulation. 
It offers faster simulation methods compared to other options, making it ideal for modeling and developing congestion algorithms and new network protocols.
The role of htsim in the Ultra Ethernet Consortium (UEC) standards development is to support the transport layer working group's work on congestion control mechanisms.

In UEC, htsim:

- provides a platform for continuous implementation and development of UEC transport layer.
- is used to simulate and run different topologies and scenarios, helping to identify issues in the current specifications and estimate the throughput and latency for given parameters like topology, flow matrix and congestion configuration.
- provides a reference for users and developers to run simulations with different configurable parameters for various scenarios and algorithms


htsim's role is deliberately focused on congestion control.

UEC's htsim is not:

- a complete implementation of the UEC transport specification.
- a standard in any way; specifically, it is not part of the official UEC standards release.
  While we aim to match the spec as closely as possible, there might be discrepancies between the UEC CMS specification and the simulator.
  Only the official CMS specification is significant, the simulator is not.


# Getting Started

Check the [README](htsim/README.md) file in the `htsim/` folder.
