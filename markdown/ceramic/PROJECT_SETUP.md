# 🏺 What is Ceramic?

Most of the information on today’s internet is stored in **walled garden databases**, not accessible to the outside world. If you don’t have direct access to the database or if there is no API exposed by the application, you might need to go and look around somewhere else. This results in data being duplicated and locked away in many different databases.

What if there was one place where you could get all the relevant content you need? What if content was open sourced the same way code is open-sourced using GitHub? That’s exactly the promise of Ceramic. **Ceramic is a platform for creating, hosting and sharing streams of data in decentralized way.** Open-source content which can be easily shared between applications using just one SDK rather than dozens of different external APIs. But always secured using your private keys.

Read more on the [official Ceramic docs](https://blog.ceramic.network/what-is-ceramic/)

# 🆔 What is IDX?

IDX is a multi-platform **identity protocol** that replaces centralized user tables with a decentralized alternative. It allows to build up a unified digital identity consisting of all their data while enabling developers to break down silos and freely share users' data between applications.

Read more on the [official IDX docs](https://developers.idx.xyz/learn/welcome/). It has some great diagrams and a glossary.

# 🤓 Stream, StreamTypes and DIDs

Two important concepts with Ceramic network are **Streams** and **StreamTypes**. Streams are nothing more than append-only logs of commits stored on IPFS. StreamTypes, on the other hand, are functions applied to those logs.

A critical responsibility of StreamTypes is the authorization of users to perform write operations to a stream. Different StreamTypes might need different levels of authorization. One of the authentication mechanisms that StreamTypes supports is **DIDs**, the W3C standard for decentralized identifiers. DIDs are used to associate globally unique, platform-agnostic string identifiers with a DID document where all the data required for signature verification and encryption is stored.

The DID is essential to IDX. With IDX, there is no more need for juggling API Keys for different external services to access data generated by users on various applications.
