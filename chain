# The Web3 公链开发教程大纲

公链是 Web3 底层最大的基础设施，也是构建各种 Web3 应用项目的基础之一。我们都知道，公链是一种去中心化的区块链网络，它提供了一种透明、安全、可靠的方式来记录和验证交易。在 Web3 项目中，公链扮演着关键角色，它们为去中心化应用程序（DApps）提供了基础设施和支持。

提到公链，我们很快就能想到的是一下这些项目：
- 比特币（Bitcoin）：作为第一个区块链和加密货币，比特币被视为数字货币的黄金标准之一。
- 以太坊（Ethereum）：以太坊是一个智能合约平台，它允许开发者构建和部署去中心化应用程序（DApps）。
- 比特币的 Layer2 解决方案：这些方案旨在通过在比特币区块链之上构建第二层协议来提高比特币网络的吞吐量和扩展性。
- 以太坊的 Layer2 解决方案：这些方案旨在提高以太坊网络的吞吐量和扩展性，同时保持与以太坊的安全性和去中心化特性。
- Cosmos：Cosmos是一个面向区块链互操作性的生态系统，它旨在解决区块链之间的互操作性和可扩展性问题。
- Solana：Solana是一个高性能的区块链平台，旨在支持大规模应用程序和去中心化金融（DeFi）项目。
- Aptos 和 Sui: 高性能的区块链平台, 使用 move 语言做为智能合约开发语言。
- 各种 AppChain 项目：AppChain是指针对特定应用场景或行业需求构建的定制化区块链网络，它们通常与公链相互连接，提供了更高的灵活性和定制化功能。

这里要说明的是，在 Bitcoin 和 Ethereum Layer2 解决方案中，目前最值得学习还是 Ethereum Layer2。其模块化的结构提供了更高的扩展性和灵活性，为构建高性能和可扩展的去中心化应用提供了有效的解决方案。掌握其中涉及的基础设施，如数据可用层、去中心化排序器、Rollup 模块(op rollup 和 zk rollup)、欺诈证明和零知识证明等，对于深入理解和应用Layer2技术至关重要。

对于初学者来说，从学习 Bitcoin 入手是一个很好的起点，因为 Bitcoin 的设计和实现相对简单清晰，可以帮助初学者建立对区块链技术的基础理解。而随着对区块链技术的逐步深入，学习 Ethereum 和 Cosmos 等更复杂的公链项目可以帮助开发者掌握更广泛的技术和应用领域。

公链项目包罗万象，涵盖的知识点也特别多，做为公链开发者，必然要学习下面的知识点。

## 1. 公链基础知识

- 区块链的基本概念
  - 区块。
  - 交易
  - 默克尔树
  - 区块头
  - 公钥加密算法
  - 共识算法
  - 智能合约
  - 状态树
  - 虚拟机
- 去中心化网络介绍

## 2. 共识算法 

- 共识算法的基本概念
- Pow:  工作量证明，主要在 Bitcoin, Ethereum(1.0), Litecoin, Conflux, Dogecoin 等项目中使用。
- dPow: 延迟工作量证明，主要在 Komodo 项目中使用
- Pos：权益证明，主要在Ethereum(2.0),  Peercoin 等项目中使用。
- Poa：权威证明，主要在 Ethereum Kovan Testnet, xDai, VeChain 等项目中使用
- Poh：历史证明，Solana 共识算法
- Dpos：委托权益证明，主要在 BitShares, Steemit, EOS , Lisk 和 Ark 等项目中使用
- Paxos:  Paxos 算法，ZooKeeper 使用，ZooKeeper 用于联盟链场景
- Raft：Raft 算法，在联盟链中用得比较多
- PBFT：拜占庭容错算法，在 HyperLedger Fabric(<1.0 版本), Stellar, Ripple 和 Dispatch 等项目中使用
- dPBFT：授权拜占庭容错，NEO 项目中使用
- rBPFT：轮流拜占庭容错
- Tendermint-BFT：Tendermint-BFT 算法，使用 cosmos sdk 的很多项目都使用该共识算法
- Avalanche-BFT：Avalanche-BFT 算法，主要在 Avalanche 中使用
- HotStuff-BFT：HotStuff-BFT 算法，Aptos-BFT 算法基于 HotStuff
- Aptos-BFT：Aptos-BFT 算法，主要在 Aptos 项目中使用

## 3. 密码学
  
- 和钱包教程重合的部分这里不再列出来
- 零知识证明简介
- 算法介绍
  - STARK 与 SNARK
    - Kzg
    - Groth16
    - Sonic
    - Fractal
    - Halo2
    - SuperSonic
    - Marlin
    - Plonk
- 零知识证明应用场景分析
- 中国国家密码学算法(国密)

## 4. 数据库
  
- LevelDB 基本原理与小型项目实战
- RocksDB 基本原理与小型项目实战
- MongoDB 基本原理与小型项目实战

## 5. 网络协议
  
- TCP/UDP/IP 协议
- P2P 通信信息协议
- RPC 和 gRPC 通信协议
- JSON-RPC 通信协议
- HTTP/HTTPS 通信协议
  
## 6. Bitcoin
  
随着 Bitcoin Layer2 的发展，Bitcoin 生态也越来越受大家的关注，深入学习 Bitcoin 的运行机制也变得越来越重要，对于公链开发者来说，需要掌握 Bitcoin 以下知识点：
- 搭建比特币钱包节点
- 比特币 UTXO 模型
- 比特币 POW 共识算法原理和代码分析
- 比特币底层数据结构和算法
- 比特币的区块组织形式
- 比特币各种地址的生成原理以及使用场景
- Taproot如何让比特币受益
- 比特币在什么条件下会产生回滚
- 比特币 RPC 接口的作用
- ElectrumX 和比特币如何协作为去中心化钱包服务
- 比特币状态通道和闪电网络的原理
- RGB 和 RGB++ 协议
  
## 7. Ethereum
  
- Ethereum RPC 服务节点搭建
- Ethereum 使用的签名算法
- Ethereum 各套带前缀 RPC 接口的作用
- Ethereum 底层数据结构和算法
- EVM 原理及源码
- EVM 各 op-code 的作用
- Ethereum 区块重组和回滚机制
- Ethereum 重要的 EIP 协议分析
- Ethereum 有哪些客户端，各客户端能实现什么功能
- ETH2.0
  - Ethereum 信标链的共识机制
  - 质押 ETH 给信标节点原理与代码实战
  - LSD 项目的基本原理
Ethereum 分片链(EIP4844)的原理和实现方式

## 8. 主流的 DA 项目
  
- EigenDA 
  - EigenDa 基本原理解读
  - EigenDa 源码解读
  - 交易数据 Rollup 到 EigenDa 项目实战
- Celestia
  - Celestia 基本原理解读
  - Celestia 源码解读
  - 交易数据 Rollup 到 Celestia 项目实战
- NearDA
  - NearDA 基本原理解读
  - 交易数据 Rollup 到 NearDA 项目实战
- Anytrust
  - Anytrust 基本原理解读
  - 交易数据 Rollup 到 Anytrust 项目实战
- Eip4844
  - Eip4844 基本原理解读
  - Eip4844 源码解读
  - 交易数据 Rollup 到 Eip4844 项目实战
DA 的实现原理及其类似，使用的技术也是类似的，例如都用到 BLS 签名算法，KZG 零知识证明算法, 纠栅码编解码。只是安全保障源不一样，Eip4844 有 Ethereum 链保证安全性，EigenDA 由 EigenLayer 重新质押协议保证安全性，安全性继承自以太坊；Celestia 和  Anytrust 的安全性由 DAC 委员会来保证。

## 9. Bitcoin Layer2
  
- Stacks 架构以及原理分析
- Nervos 
  - Nervos 基本原理
  - Nervos 架构解析
  - Nervos RGB++ 协议解析
上面两个项目是目前技术解决方案比较好的 Bitcoin Layer2 (Bitocin 侧链)项目，其他几乎都是抄 ETH Layer2 的实现方案，而且大多做得四不像，的这里不做探讨。

## 10.Ethereum Layer2

- Layer2 的基本概念和主流项目分析
- Arbitrum Nitro
  - Nitro 架构解析
  - 深入理解 Nitro 跨链调用过程及 ETH 和 ERC20 的充值提现解析 
  - Nitro Rollup 流程详解 
  - Nitro Fraud proof 简析
  - 如何在本地启动 Nitro devnet 网络 
  - Nitro l1->l2, l2->l1, rollup 交易数据, 交易状态同步实战 
  - 如何基于 Nitro 开发自己的 Layer2 链 
- Optimistim
  - Op-Stack 架构解析
  - 深入理解 Op-stack 跨链调用过程及 ETH 和 ERC20 的充值提现解析 
  - Op-stack Rollup 流程详解 
  - Op-stack Rollup 流程改造到 EigenDa 实战，
  - Optimistim op-node json rpc 
  - Optimistim 区块推导过程详解 
  - 如何在本地启动 op-stack devnet 网络 
  - 如何使用 op-stack sdk 进行充值提现测试 
  - op-stack l1->l2, l2->l1, rollup 交易数据, 交易状态同步实战 
  - 如何基于 op-stack 开发自己的 Layer2 链 
  - Op-stack 配置项详解
  - Op-stack 服务运行状态监控
  - 基于 sepolia 部署一个 Layer2 网络 
- PolygonZkEvm
  - PolygonZkEvm 架构解析
  - 深入理解 PolygonZkEvm 跨链调用过程及 ETH 和 ERC20 的充值提现解析 
  - PolygonZkEvm Rollup 流程详解 
  - PolygonZkEvm zk proof 流程和细节剖析
  - 如何在本地启动 PolygonZkEvm devnet 网络 
  - PolygonZkEvm l1->l2, l2->l1, rollup 交易数据, 交易状态同步实战 
  - 如何基于 PolygonZkEvm 开发自己的 Layer2 链 
- Scroll 架构以及原理分析
- ZksyncEra 架构以及原理分析
- Linea 架构以及原理分析
- Starknet 架构以及原理分析

以上这些项目都是以太坊 Layer2 中的原创项目，吃透这些 L2 项目，绝对是 L2 界的大牛，L2 的学习要点都类似, 主要从以下这些角度去进行学习

Rollup 模块: 数据 rollup 和证明 rollup, 数据一般 rollup 到以太坊或者其他第三方 DA，证明 rollup 到以太坊上，由以太坊上的合约进行验证。

Sequencer: 基于 geth 改进的适配 L2 的 EVM 客户端，有的项目是单 Sequencer，有的项目是去中心化 Sequencer。

验证和证明系统：证明系统分为 Zk proof 和 Fraud proof

ZK proof: 链下 Zk Prove 生成证明，链上 Verifier 合约验证

Fraud proof：链下 rollup 关键交易数据，一旦发生欺诈，链下执行找到不同的 op-code, 链上合约进行验证。

跨链桥：承载 L1<->L2 的资产和消息的跨链

## 11. Cosmos
  
- Cosmos 的 SDK X 目录下的各原生模块的功能和源码
- IBC 跨链通信协议
- Tendermint 项目实现原理和源码
- CosmWarsm 实现细节
- interchain-security 原理以及实现细节
- Cosmos 和 EVM 模块结合实现细节(Ethermint 项目)
- 如何基于 Cosmos 开发自己的公链项目
- 如何基于 Cosmos 开发 AppChain 项目

## 12. 其他公链
- Solana 基本原理与架构解析
- Sui  基本原理与架构解析
- Aptos 基本原理与架构解析
  
## 13. Layer3 AppChain 
  
- 什么是 Layer3
- 市场主流的 Layer3 AppChain 是怎么做的
- 如何设计开发一条 Layer3 AppChain
- DappLink L3 AppChain 是如何实现的
  - 跨链互操作协议解决方案
  - 多重质押协议解决方案
  - AppChain 解决方案

## 14. 公链项目实战

以上是从合约，公链，钱包角度出发学习需要掌握的知识，在我们整个课程体系中，我们还会做以下项目实战
- 基于 DappLink Layer3 的治理和托管模块开发保险产品
- 基于 DappLink Layer3 的交易模块开发体验和中心化交易所一致的去中心化交易所
- 基于 LinkLayer 安全质押模型的应用开发
- 基于 DappLink Layer3 游戏模块开发一道两个小游戏
- 基于 DappLink Layer3 社交模块和 Parapack 钱包开发社交应用





