---
title: Solri
subtitle: An envolving proof-of-work blockchain experiment.
layout: default
toc_pages:
  - url: https://github.com/solri/specs
    title: Specification
    subtitle: Github Repository for Solri Specifications
    abstract: >
      Read the current specifications of Solri network.
  - url: https://github.com/solri/solri
    title: Reference Implementation
    subtitle: Github Repository for the Rust Implementation
    abstract: >
      We are still working towards the initial minimal viable product 
      (MVP), and you can follow our progress there.
  - url: https://riot.im/app/#/room/#solri:matrix.org
    title: Community
    subtitle: The Matrix Chatroom
    abstract: >
      Follow the latest news of Solri and discussions. We also have a
      [Discord](https://discord.gg/DZbg4rZ) server.
---

Highly inspired by
[Substrate](https://github.com/paritytech/substrate) by Parity
Technologies and [Serenity](https://github.com/ethereum/eth2.0-specs/)
by Ethereum Foundation, **Solri** is a proof-of-work blockchain
designed to be simple, self-envolve and stateless.

<section markdown="1">

## About Solri

In particular, Solri's design goals are to:

* Become a **pure** coin, in most possible aspects that blockchain
  community cares about. This includes having **no premine** and
  establishes **fair launch**.
* Use well-established **Proof of Work** consensus algorithm, and at
  the same time, allows it to change to either become ASIC-friendly or
  ASIC-resistent.
* Most essential functions of the blockchain is coded into
  **WebAssembly** runtime. This makes it so that the blockchain can
  evolve and upgrade features **without hard fork**. In fact, we aim
  to never conduct any hard fork!
* Have clear and simple **specification** to make supporting multiple
  implementations easier.
* Be **stateless**. To fully verify a new block, you will only need
  the parent block together with the parent block's runtime
  output. This reduces the bare minimal storage requirement for full
  node to nearly zero. In practice, clients can selectively choose to
  only store states it cares about.
  
Before we go on, it is important to note that Solri is currently
entirely a hobby project, and it's really early stage.

</section>

<section markdown="1">

## Resources

{% include toc.html %}

</section>
