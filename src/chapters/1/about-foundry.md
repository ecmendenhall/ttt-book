# About Foundry
Throughout these workshops, we'll be using [Foundry](https://github.com/gakonst/foundry) to develop, test, and deploy our smart contracts. Foundry is a suite of command line tools for interacting with Ethereum and testing smart contracts, written in Rust. It is the faster, friendlier successor of an earlier project called [Dapptools](http://dapp.tools/). 

Dapptools has a well deserved reputation as a powerful tool. The source of its superpowers is [HEVM](https://github.com/dapphub/dapptools/tree/master/src/hevm), a Haskell implementation of the Ethereum Virtual Machine that is specifically designed for symbolic execution, debugging, and testing smart contracts. HEVM makes it easy to write property-based tests, write proofs about the behavior of your contracts, and step through the execution of your code at a low level.

Foundry's HEVM equivalent is [revm](https://github.com/bluealloy/revm), a Rust implementation of the EVM. It's much faster, although it doesn't yet support symbolic execution and a few other advanced features of HEVM.

Foundry is friendlier than Dapptools, but it still has a learning curve. I think of it as a little bit like the Vim text editor: very powerful, very Unixy, and a little overwhelming at first. But just like Vim, I think the payoff of learning the tool is worth the effort. Starting this project from the ground up with Foundry is a great way to learn it from scratch.

> **Foundry Resources**
>
> The [Foundry Book](https://book.getfoundry.sh/) is the definitive resource if you want to read more about Foundry. [How to Foundry](https://www.youtube.com/watch?v=Rp_V7bYiTCM) is an excellent introductory video. If you need help, try the official [support Telegram](https://t.me/+pqodMdZCoQQyZGI6).
