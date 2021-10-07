# cheqd: Node Documentation

cheqd is a purpose-built network for decentralised identity built using [Cosmos SDK](https://github.com/cosmos/cosmos-sdk) and [Tendermint](https://github.com/tendermint/tendermint).

## Quick start for joining cheqd Testnet

Getting started as a node operator on the cheqd network testnet requires the following steps:

1. [Install the `cheqd-node` software](docs/setup-and-configure/readme.md) connected to the [existing seed nodes](https://github.com/cheqd/cheqd-node/blob/main/persistent_chains/testnet/seeds.txt) on the testnet. Use hosting platform of your choice.
2. When you have a node successfully installed, please fill out our [**node operator onboarding form**](http://cheqd.link/join-testnet-form) so that you can acquire testnet tokens required for staking on the network. You will need to have the following details on hand to fill out the form:
   1. Node ID for your node
   2. IP address / DNS record that points to the node \(if you're using an IP address, a static IP is recommended\)
   3. Peer-to-peer \(P2P\) connection port \(defaults to `26656`\)
3. Once you have received your tokens, [promote your node to a validator](docs/setup-and-configure/configure-new-validator.md).
4. If successfully configured, your node would become the latest validator on the cheqd Testnet! Say hi to the other node operators on the [\#testnet-node-operators](https://cheqd-community.slack.com/archives/C029NSCSA75) channel.

Any time you have questions or need support, join our [**cheqd Community Slack** ](http://cheqd.link/join-cheqd-slack) and [ask for help](https://cheqd-community.slack.com/archives/C02AQ9UK4HY).

## Usage

Once installed, `cheqd-node` can be controlled using the [cheqd Cosmos CLI reference guide](docs/cosmos-cli.md).

### Currently supported functionality

* Basic token functionality for holding and transferring tokens to other accounts on the same network
* Creating, managing, and configuring accounts and keys on a cheqd Cosmos ledger
* Staking and participating in public-permissionless governance

### Upcoming functionality

A non-exhaustive list of future planned functionality \(not necessarily in order of priority\) is highlighted below:

* Updated Cosmos genesis parameters for cheqd Testnet along with updated guidance on token functionality
* DID method specification
* Creating and querying DIDDocs
* Creating and managing Verifiable Credentials anchored to DIDs on cheqd testnet
* Governance framework for public-permissionless self-sovereign identity networks

We plan on adding new functionality rapidly and on a regular basis. We are also exploring mechanisms to showcase our product roadmap and gather feedback from our community members. We welcome feedback on our [cheqd Community Slack](http://cheqd.link/join-cheqd-slack) workspace.

## Release artefacts

Our instructions on [how to set up a new node](docs/setup-and-configure/readme.md) covers: 

1. Minimum system requirements and prerequisites
2. Installation process using Debian \(.deb\) package, binary, and Docker
3. Fetching basic node information after installation

We provide packaged releases available for node installation, depending on the method you prefer.

### Debian \(.deb\) package releases

* Understand an [overview of what the `cheqd-node` Debian \(.deb\) package]() configures.
* If you already have an existing `cheqd-node` installation that was done using the .deb package, find out how to [upgrade your node using the .deb package]().

### Docker

* We provide [pre-built Docker containers for `cheqd-node`](https://github.com/orgs/cheqd/packages?repo_name=cheqd-node) for those who wish to install local / testnet nodes using Docker.
* You can [build your own Docker container images for `cheqd-node`]() and use Docker Compose to [set up a local network consisting of multiple Docker nodes](docker/docker_compose.md) for testing purposes.
* You can also [use this image to set up a local network consisting of multiple node processes in a single container]().

## Building from source

`cheqd-node` is created with [Starport](https://github.com/tendermint/starport). If you want to build a node from source or contribute to the code, please read our guide to [building and testing](docs/building-and-testing.md).

### Creating a local network

If you are building from source, or otherwise interested in running a local network, we have [instructions on how to set up a new network](docs/setting-up-a-new-network.md) for development purposes.

## Community

The [**cheqd Community Slack**](http://cheqd.link/join-cheqd-slack) ****is our chat channel for the open-source community, software developers, and node operators.

Please reach out to us there for discussions, help, and feedback on the project.

### Social media

Follow the cheqd team on our social channels for news, announcements, and discussions.

* [@cheqd\_io](https://twitter.com/cheqd_io) on Twitter
* [@cheqd](https://t.me/cheqd) on Telegram \(with a separate [announcements-only channel](https://t.me/cheqd_announcements)\)
* [Medium](https://blog.cheqd.io/) blog
* [LinkedIn](http://cheqd.link/linkedin)

