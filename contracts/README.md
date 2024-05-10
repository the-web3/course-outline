# The Web3 智能合约开发教程大纲


对于绝大多数开发者来说，最熟悉的智能合约开发语言是基于 EVM 系列链开发的应用的 Solidity；大家也许听过 Rust 和 Move 等合约开发语言，但是真正基于 solana, sui 和 aptos 做过开发的开发者并不是很多；绝大多数人可能都不知道 Python, Node 和 Clarity 等编程语言也可以做为智能合约开发语言，故基于 Tezos 和 Stacks 等链开发应用，可能很多人都闻所未闻。

The Web3 的课程主要重点放在 Solidity 智能合约开发语言和基于 EVM 链的 Dapp 开发实战；次重点是 Rust 和 Move 智能合约开发语言和基于 Solana, Sui 和 Aptos Dapp 开发实战；当然我们也会涉及在 Tezos，Stacks 和 Ton 等链上的开发简单的智能合约。

## 1. 智能开发准备

在智能合约开发之前，我们需要做一些准备，区块链基础知识和课程涉及到的链的简单介绍

- 区块链基础知识讲解
- 以太坊以及以太坊虚拟机简介
- Solana, Aptos 和 Sui 简介
- 非主流代表项目 Ton, Tezos  和  Stacks 简介
  
## 2. 编程语言

针对智能合约开发语言，本教程主要针对 Solidity, Rust 和 Move，其他编程语言如 Node, Python 等传统互联网的人也会，而且也是非主流智能合约开发语言，Clarity 这样的编程语言又晦涩难懂，我们这里不做过多的探讨。

### 2.1 Solidity

Solidity 基本语法
Solidity 编码规范
Solidity 高级特性
实际编码中如何选用 Solidity 数据结构
合约与合约之间的调用方式
合约 ABI
ERC 协议
- ERC20
- ERC721 和 ERC1155
- ERC1967
- ERC2535
- ERC4337
合约开发工具
- Remix
- Hardhat
- Foundry
合约审计工具
- Slither
- Mythril
- Oyente
- Securify
- SmartCheck
- Manticore
- Echidna
- Teether
- 商用合约审计工具
Oz 类库介绍
合约审计中的常见安全性漏洞分析
合约升级的方式以及实际操作
将合约编译成其他语言方便调用
常见的合约攻击方式以及如何避免

### 2.2 Rust

Rust 基本语法
理解 Rust 所有权
Rust 枚举和模式匹配
Rust 包管理
Rust 高级特性
- 集合、错误处理和自动化测试
- Rust I/O 项目
- Rust 智能指针
- Rust 并发编程
- Rust 的面向对象编程特性
- 模式与匹配
rust 实现主流的数据结构与算法
rust web 框架介绍
- rust web 框架之 Poem
- rust web 框架之 Actix-web
- rust web 框架之 Hyper
- rust web 框架之 Rocket
- rust web 框架之 Warp
- rust web 框架之 Nickel
- rust web 框架之 Tide
rust Orm
rust 实现 Grpc server 和 Client
Zengo MPC 代码实现

### 2.3 Move

- Move 基本语法
- Move 编码规范
- Move 合约审计
- Sui 和 Aptos Move 合约开发
  
## 3. 项目实战

- 发行代币开发实战(含非主流链的合约开发教程)
- 发行 NFT 集开发实战
- Dex 和质押协议开发实战
- 跨链互操作协议开发(针对 EVM 链)实战
- ZKP Verifier 合约开发实战
- GameFi, SocialFi 开发实战
- 合约事件监听器开发实战




