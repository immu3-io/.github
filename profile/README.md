# Introduction to IMMU3

### Permissionless "on-chain" communication protocol stack that can support 1000s of communication dApps to evolve on Web3. ### 

![immu3 creative](https://github.com/immu3-io/static-assets/blob/323c63bb25f4e923589422c156895c0fe3f30153/image/immu3_creative.png)

Immu3 is an on-chain communication technology infrastructure and [4thTech](https://github.com/4thtech) **Level 1** integrator. It utilizes a permissionless agnostic protocol stack that can support 1000s of on-chain communication dApps to evolve on Web3. To achieve full immutability and self-custodianship every email, message, or data file transfer is represented as an L1 or L2 TX (i.e. transaction). Users' communication and data are accessible only with his or her private key.

_"Users will always be free to move and access their communication or data between dApps, while the developers will always have permissionless access to build communication-specific applications."_

## Core Primitives

While various use cases are possible, let's use dMail and dChat as examples. The dChat W2W message exchange happens on-chain as one short message represents one L1 or L2 blockchain transaction. As dMail is data heavier, lite encrypted JSON objects are created to hold dMail metadata. The link to this metadata and checksum is recorded on the chain as a blockchain transaction. The same goes for W2W data file transfers where; 1 data file package transfer = 1 L1/L2-TX. So again, the core primitive described by the formula below applies; 

💡**1 email/message/data-exch = 1 L1/L2-TX**

Every wallet becomes an on-chain identity, and the message or data vault can be accessible (i.e. decrypted) only with users' private keys! There are three encryption options available within the protocol; (1) custom encryption; (2) AES-randomly generated secret key (i.e. Advanced Encryption Standard), and; (3) AES secret key produced by ECDH (i.e. Elliptic-Curve Diffie-Hellman); 

💡**Not your keys = not your email/message/data**

## Infrastructure by Layers

Zooming out, the stack is quite straightforward. As shown in the schematic, there are dApps built on top of the [SDK v.1](https://github.com/4thtech/4thtech-sdk-js), powered by [Protocol v.1](https://github.com/4thtech/smart-contracts), encryption, [PollinationX](https://github.com/pollinationx/) storage and blockchain networks. To be able to establish Web3's first communication standard, Protocol v.1 will be deployed on many L1s and L2s. Please check the [Immu3 multi-chain](https://wiki.immu3.io/infrastructure/protocol-v.1/multi-chain) table to follow the standard deployment. To support enterprise and mobile "on-chain" communication at scale, the deployment of communication-specific blockchain would be needed in the future.

![immu3 by layers](https://github.com/immu3-io/static-assets/blob/b90554bcca1a4d7696079beb1a0cab5265129afa/image/infrastructural-layer-schematic-immu3.svg)

## Immu3 dApp Ecosystem Deployment Table

| ****                    | **TestNet** | **MainNet** | **GitHub** | **Chrome Store** | **Manual** |
|:-------------------------:|:-------------:|:-------------:|:------------:|:------------------:|:------------------:|
| **dMail**               | [Go](https://testnet.immu3.io)       | [Go](https://app.immu3.io)            | [Go](https://github.com/immu3-io/app.immu3.io)           | /                 | [Go](https://wiki.immu3.io/dapps-and-clients/intro-to-dmail)                 |
| **dChat**               | [Go](https://testnet.immu3.io)            | [Go](https://app.immu3.io)            | [Go](https://github.com/immu3-io/app.immu3.io)           | /                 | [Go](https://wiki.immu3.io/dapps-and-clients/intro-to-dchat)                 |
| **W3XShare**            | [Go](https://testnet.w3xshare.com)            | [Go](https://w3xshare.com)            | [Go](https://github.com/immu3-io/w3xshare.com)           | /                 | [Go](https://wiki.immu3.io/dapps-and-clients/intro-to-w3xshare)                 |
| **PX Drive**            | [Go](https://testnet.drive.pollinationx.io)            | [Go](https://drive.pollinationx.io)            | [Go](https://github.com/PollinationX/pxDrive)           | /                 | [Go](https://wiki.immu3.io/dapps-and-clients/intro-to-px-drive)                 | 
| **PX Dashboard**        | [Go](https://testnet.pollinationx.io)            | [Go](https://app.pollinationx.io)            | [Go](https://github.com/PollinationX/dapp)           | /                 | [Go](https://wiki.pollinationx.io/overview/px-dashboard)                 |
| **Encryptor Extension** | /           | /            | [Go](https://github.com/4thtech/encryptor-extension)           | [Go](https://chrome.google.com/webstore/detail/encryptor/feolajpinjjfikmmeknkdjbllbppojij?hl=en)                 | [Go](https://wiki.immu3.io/dapps-and-clients/encryptor-extension)                 |

## Start Building

A permissionless Level 2 integrator licence is available via Level 1 integrator [Immu3](https://wiki.immu3.io/) and is perfect for teams wanting to build their own on-chain communication dApps. Enterprise Level 1 integrator licence is available via Block Labs and is meant for traditional businesses or offices, L1s, wallets, and existing applications.

💡**SDK v.1** provides abstractions to assist you with interacting with the v.1 Protocol smart contracts in a Typescript/Javascript environment. With the SDK, you can manipulate data that has been queried from the EVM using libraries that assist with needs such as data modelling, protection from rounding errors, and compiling time-enforced typing.

💡**dMail & dChat white-label framework** enables fast and easy builds. White-label-based modern minimalistic design style emphasizes simplicity with simple intuitive but effective navigation and setup system. A simple user interface has been developed to offer a step-by-step setup enabling the best possible user experience.

 ****            | **Repo** | **Wiki** |
:---------------:|:--------:|:--------:|
 **SDK v.1**     |     [Go](https://github.com/4thtech/sdk-js)     |     [Go](https://wiki.4thtech.io/docs/sdk)     |     
 **White-label** |      [Go](https://github.com/4thtech/white-label-client)    |     [Go](https://wiki.4thtech.io/docs/white-label)     |

## Interested in reading more?

In-depth research and clarifications can be found in
the projects [Thesis](https://bit.ly/immu3-thesis)

## Contact

If you want to start building on-chain communication dApps in the pre-public phase please DM us on [Twitter](https://twitter.com/immu3_io)
