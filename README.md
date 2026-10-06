# Awesome HOPR [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://hoprnet.org"><img src="https://raw.githubusercontent.com/hoprnet/hopr-assets/master/v1/logo/hopr_logo_padded.png" align="right" width="150" alt="HOPR logo"></a>

> A curated list of projects, tools, and resources related to HOPR, the open incentivized mixnet for privacy-preserving point-to-point data exchange.

HOPR routes packets through multiple relay nodes using Sphinx packet encryption, mixing, and cover traffic, and pays relays with probabilistic tickets via Proof of Relay. These resources help you run nodes, build on the protocol, and dig into how it works.

## Contents

- [Official Resources](#official-resources)
- [Node Operation](#node-operation)
- [Libraries and SDKs](#libraries-and-sdks)
- [Infrastructure](#infrastructure)
- [Developer Tools](#developer-tools)
- [Applications](#applications)
- [Research](#research)
- [Community](#community)

## Official Resources

- [Documentation](https://docs.hoprnet.org) - Guides for running nodes, staking, tokens, and core protocol concepts.
- [hopr-lib API Reference](https://hoprnet.github.io/hoprnet/hopr_lib/index.html) - Rustdoc for the referential Rust implementation of the protocol.
- [RFCs](https://rfc.hoprnet.org) - Specifications of the HOPR protocol, from packet format to incentives and path selection.
- [Staking Hub](https://hub.hoprnet.org) - Web app for adding nodes and managing your HOPR Safe and staking module.
- [Website](https://hoprnet.org) - Official project website.

## Node Operation

- [ansible-hoprd](https://github.com/hoprnet/ansible-hoprd) - Ansible role for provisioning and managing `hoprd` nodes.
- [DAppNode Package](https://github.com/dappnode/DAppNodePackage-Hopr) - Run a HOPR node as a DAppNode package.
- [Homebrew Tap](https://github.com/hoprnet/homebrew-hoprd) - Install `hoprd` and run it as a Homebrew service.
- [hopli](https://github.com/hoprnet/hopli) - CLI for operator workflows: identities, node funding, Safe and module setup, and on-chain configuration.
- [hoprd](https://github.com/hoprnet/hoprd) - Full HOPR node daemon exposing a REST API.
- [hoprd Kubernetes Operator](https://github.com/hoprnet/hoprd-operator) - Kubernetes operator built on kube-rs for managing `hoprd` nodes.
- [Node Admin UI](https://github.com/hoprnet/node-admin-ui) - Web app for managing a `hoprd` node through its REST API.

## Libraries and SDKs

- [blokli-client](https://github.com/hoprnet/blokli-client) - Rust client for the Blokli GraphQL API and transaction endpoints.
- [Edge Client](https://github.com/hoprnet/edge-client) - HOPR protocol client without the heavy RPC integration of a full node.
- [hopr-sdk](https://github.com/hoprnet/hopr-sdk) - TypeScript SDK wrapping the `hoprd` REST API for node, account, and messaging operations.
- [hoprnet](https://github.com/hoprnet/hoprnet) - Referential Rust implementation of the HOPR protocol (`hopr-lib`).

## Infrastructure

- [Blokli](https://github.com/hoprnet/blokli) - Indexer for on-chain HOPR smart contract events, serving the HOPR Indexer API.
- [Smart Contracts](https://github.com/hoprnet/contracts) - Solidity contracts powering the HOPR mixnet, with current deployment addresses.

## Developer Tools

- [HOSE](https://github.com/hoprnet/hose) - Web-based session explorer that collects OTLP telemetry to debug sessions across entry, relay, and exit nodes.
- [hopr-wireshark](https://github.com/hoprnet/hopr-wireshark) - Wireshark dissector that decrypts and dissects HOPR packets from a local cluster.
- [Skills](https://github.com/hoprnet/skills) - Claude Code plugin marketplace with agent skills grounded in the HOPR RFCs.

## Applications

- [Gnosis VPN](https://vpn.gnosis.eth.limo) - Privacy-preserving VPN built on the HOPR mixnet ([client source](https://github.com/gnosis/gnosis_vpn-client)).
- [myTokenTracker](https://mytokentracker.xyz) - Demo showing how dApp users can be identified by linking their Ethereum address to their IP address.

## Research

- [Core Concepts](https://docs.hoprnet.org/core/what-is-hopr) - Explainers on mixnets, Proof of Relay, probabilistic payments, and cover traffic.
- [ct-research](https://github.com/hoprnet/ct-research) - Cover traffic research at HOPR.
- [RFC Sources](https://github.com/hoprnet/rfc) - Source repository for the HOPR protocol RFCs.

## Community

- [Discord](https://discord.com/invite/5FWSfq7) - Community chat server.
- [Medium](https://medium.com/hoprnet) - Official blog.
- [Reddit](https://www.reddit.com/r/HOPR/) - Community subreddit.
- [Telegram](https://t.me/hoprnet) - Official Telegram channel.
- [X](https://x.com/hoprnet) - Official account for announcements.
- [YouTube](https://www.youtube.com/channel/UC2DzUtC90LXdW7TfT3igasA) - Official video channel.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
