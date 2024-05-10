# 来 The Web3, 学习史上最全面的区块链教程，挑战高薪

## 1. 概述
The Web3 是一个专注 Web3 技术解决方案设计与开发、技术教程设计与开发、Web3 项目投研分析和 Web3 项目孵化，旨在将开发者，创业者，投资者和项目方联系在一起的社区；其前身是 Savour Labs，目前已孵化出 Layer3 AppChain 项目 DappLink。

为了帮助更多的 Web2 开发者迅速进入 Web3，让已经处于 Web3 开发者深入了解区块链知识，让更多开发者更好的设计开发自己的产品;  The Web3 社区计划开发一系列 Web3 教程， 从编程语言到项目实战，包括已有项目设计理念分析，产品设计，项目架构设计等，全方位帮助 Web3 开发者成长。

本教程将从合约，钱包和公链项目设计，产品设计和项目开发等多角度出发打造，当然整个教程是综合性的，里面也会含有前后端和运维层面的一些知识。在整个课程体系中，我们会穿插很多实战项目设计与开发，并且尽可能的将这些实战项目孵化成功之后去融资；同时，对于那些学完本教程之后，变得很优秀的开发者，我们将毫不吝啬的给大家推荐工作。

那么，学完本教程，你能获得什么？获得进入 Web3 开发的入场劵，获得远程工程的机会，获得高薪工作的机会。

学完本教程之后，将有以下这些开发岗位适合你：
- 智能合约开发工程师
- 钱包产品经理
- 交易所钱包开发工程师
- 去中心化钱包开发工程师
- 硬件钱包开发工程师
- 公链(L1/L2/L3)开发工程师
- 投研分析师
- 公链研究员
- 区块链密码学研究员

## 2. The Web3 合约开发教程
主流的智能合约编程语言有 Solidity, Rust 和 Move 等,  Solidity 是 EVM 系列公链的合约开发语言；Rust 是当前大火的 Sonala 公链智能合约开发语言，同时一些用 Rust 编写的 EVM 公链也支持 Rust 做为智能合约开发语言，例如 Zksync-rea；Move 语言是 Aptos 和 Sui 等次主流公链的智能合约开发语言。除了 Solidity, Rust 和 Move 等主流的合约开发语言之外，Python, Node 等编程语言在一些名气不大的公链里面也做为智能合约开发语言，例如 Tezos 可以使用 Python(SamrtPy)，Michelson 等做为合约开发语言，Stacks 使用 Clarity 做为智能合约开发语言。

### 2.1 编程语言

针对智能合约开发语言，本文主要针对 Solidity, Rust 和 Move，其他编程语言由于是非主流智能合约开发语言，这里不做过多的探讨。

#### 2.1.1 Solidity 

- Solidity 基本语法
- Solidity 编码规范
- Solidity 高级特性
  - 实际编码中如何选用 Solidity 数据结构
  - 合约与合约之间的调用方式
  - 合约 ABI
  - ERC 协议
    - ERC20
    - ERC721 和 ERC1155
    - ERC1967
    - ERC2535
    - ERC4337
  - 合约开发工具
    - Hardhat
    - Foundry
  - 合约审计工具
    - Slither
    - Mythril
    - Oyente
    - Securify
    - SmartCheck
    - Manticore
    - Echidna
    - Teether
    - 商用合约审计工具
- 合约升级的方式以及实际操作
- 将合约编译成其他语言方便调用
- 常见的合约攻击方式以及如何避免

#### 2.1.2 Rust

- Rust 基本语法
- 理解 Rust 所有权
- Rust 枚举和模式匹配 
- Rust 包管理
- Rust 高级特性
  - 集合、错误处理和自动化测试 
  - Rust I/O 项目
  - Rust 智能指针 
  - Rust 并发编程 
  - Rust 的面向对象编程特性
  - 模式与匹配 
- rust 实现主流的数据结构与算法 
- rust web 框架介绍 
  - rust web 框架之 Poem 
  - rust web 框架之 Actix-web
  - rust web 框架之 Hyper 
  - rust web 框架之 Rocket 
  - rust web 框架之 Warp 
  - rust web 框架之 Nickel 
  - rust web 框架之 Tide 
- rust Orm 
- rust 实现 Grpc server 和 Client
- Zengo MPC 代码实现
  
#### 2.1.3 Move

- Move 基本语法
- Move 编码规范
- Move 合约审计
- Sui 和 Aptos Move 合约开发
  
### 2.2 项目实战

- 发行代币开发实战
- 发行 NFT 集开发实战
- Dex 和质押协议开发实战
- 跨链互操作协议开发(针对 EVM 链)实战
- ZKP Verifier 合约开发实战
- GameFi, SocialFi 开发实战
- 合约事件监听器开发实战

## 3. The Web3 钱包开发教程

钱包是区块链的入口，不管是交易所，还是去中心化的应用，钱包都做为一个基础的功能而存在；我们都知道，钱包分为中心化钱包，去中心化钱包(含 AA 钱包和社交恢复钱包)，硬件钱包和托管钱包(包含多签钱包和 MPC 钱包)；四种钱包的区别主要是私钥的管理方式不一样。

中心化钱包钱包一般供给交易所使用，将完整的私钥加密之后管理在中心化的环境中，常见的管理方式有 TEE, KMS 和 CloadHSM。

去中心化钱包私钥加密之后存储在用户设备中，一般钱包私钥丢失无法找回。社交恢复钱包分为两种，密钥分片备份和守护者恢复，密钥分片技术是将用户的私钥使用门限共享秘密算法将私钥分成 N 片加密之后分发给不同的朋友存储到设备中，一旦密钥丢失，通过社交加验证的方式从朋友哪里获取 M 个密钥分片，使用 N-M(密钥拆分成 N 分，拿大其中 M 份可以恢复出完整的密钥) 逆门限共享秘密算法恢复出完整的私钥。守护者社交恢复主要是针对 EVM 系列的社交恢复钱包，由一个合约来管理整个钱包，一旦密钥丢失，发起社交恢复，由多个守护者签名一笔交易进行钱包合约的私钥替换，完成恢复的过程。

硬件钱包主要是把私钥管理在离线的硬件设备中，在硬件设备中集成钱包签名算法。

托管钱包有两种，团队资金共管钱包，一般使用多签钱包；EVM 链比较成熟的方案是 gnosis 多签，其他链还是使用多签算法实现；企业资管一般使用 MPC 钱包，MPC 是资管解决方案里面用得最多的密码学算法，运行 N 个 MPC 节点，节点之间通过多轮交互之后生成密钥片，节点与节点之间互相不知道对方生成的密钥片是什么，当需要发交易时，只需要其中 M 个节点签名交易就有效。

上面说了这么多，如果想找一份还不错的钱包开发的工作，您应该掌握哪些知识呢？我们将在下面做详细的探讨

### 3.1 密码学算法基础

- 公钥密码学基础
- DES 算法深入 
- RSA, GPG, ECDSA 和 EDDSA 算法深入
- BLS 算法深入
- 单向函数算法深入
- 门限共享密码算法深入
- MPC 算法深入

### 3.2 通信协议

- 蓝牙通信协议
- 串口通信协议
- NFC 通信协议
- P2P 通信协议

### 3.3 离线签名(含硬件钱包)

- 主流公链的交易签名前后数据组织编码细节与代码实现 
- Tee,  Kms 和 CloadHSM 等集成环境的密钥对生成和签名调度
- 通过各种通信协议调度硬件生成密钥对和交易签名等

### 3.4 中心化钱包

- 主流公链 RPC 接口，能快速组织接口扫链支持钱包出入金
- 熟悉充值，提现，归集，热转冷，冷转热和链路风控等钱包业务流程

### 3.5 去中心化钱包(含硬件钱包)

- 熟悉 BIP 协议簇
- 能快速组织主流公链 RPC 接口支持钱包转账，交易记录等
- 钱包和主流 Dapp 交互过程开发(Dapp 浏览器)

### 3.6 托管钱包

- Gnosis Safe 多签钱包流程
- MPC 底层算法实现机制
- 使用 MPC 开发托管钱包

### 3.7 项目实战

- Top40 主链扫链出入金
- Top40 离线签名
- 通过Tee,  Kms 和 CloadHSM 等集成环境实现钱包离线签名
- 通信协议实战
- 开发一个 MPC 网络
- 开发一个完整的 HD 钱包
  
## 4. The Web3 公链开发教程

公链是 Web3 项目的基础，构建 Web3 项目就必然得有公链的支撑，我们都知道，目前主流的公链包含: Bitcoin, Ethereum, Bitcoin-Layer2，Ethereum-Layer2, Cosmos, Solana 和 各种 AppChain 等项目。

一层公链最有价值且最值得学习的有 Bitcoin，Ethereum，Cosmos 和 Solana 等；如果能完全掌握 Bitcoin，Ethereum, Cosmos 和 Solana 底层设计原理及源码，就已经超越绝大多数做公链开发的工程师了。

Bitcoin Layer2 本身并不是太成熟，资本的炒作可能会导致 Bitcoin Layer2 最后是一地鸡毛，故而二层公链目前最值得学习的还是 Ethereum Layer2,。模块化的 Ethereum  Layer2 公链有以下基础设施需要学习掌握：
- 数据可用层(DA 层)
- 去中心化排序器(de sequencer)
- Rollup 模块(Rollup Services)
- 欺诈证明(Fraud Proof)
- Zk Proof(Zk Prove & Verifer)

在所有公链项目中，Bitcoin 是初学者入门必须学习的项目，然而 Bitcoin 整体开发者生态并不强大，开发者生态最强大的必然是 Ethereum 和 Cosmos。因此，如果想学习区块链，建议从 Bitcoin 入手学习，进而深入学习 Ethereum 和 Cosmos。

公链项目包罗万象，涵盖的知识点也特别多，做为公链开发者，必然要学习下面的知识点。

### 4.1 共识算法

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

### 4.2 密码学

- 公钥密码学基础
- DES 算法深入 
- RSA, GPG, ECDSA 和 EDDSA 算法深入
- BLS 算法深入
- 单向函数算法深入
- PKI 公钥体系
- 门限共享密码算法深入
- MPC 算法深入
- ZKP 算法深入
  - STARK 与 SNARK
  - Kzg
  - Groth16
  - Sonic
  - Fractal
  - Halo2
  - SuperSonic
  - Marlin
  - Plonk
- 中国国家密码学算法(国密)

### 4.3 数据库

- LevelDB
- RocksDB
- MongoDB
4.4 网络协议
- TCP/UDP/IP 协议
- P2P 通信信息协议
- RPC 和 gRPC 通信协议
- JSON-RPC 通信协议
- HTTP/HTTPS 通信协议

### 4.5 Bitcoin

随着 Bitcoin Layer2 的发展，Bitcoin 生态也越来越受大家的关注，深入学习 Bitcoin 的运行机制也变得越来越重要，对于公链开发者来说，需要掌握 Bitcoin 以下知识点：
- 搭建比特币矿工节点和钱包节点
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

### 4.6 Bitcoin Layer2(Bitocin 侧链)

- Stacks 
- Nervos
上面两个项目是目前技术解决方案比较好的 Bitcoin Layer2 (Bitocin 侧链)项目，其他几乎都是抄 ETH Layer2 的实现方案，而且大多做得四不像，的这里不做探讨。

### 4.7 Ethereum 

- Ethereum RPC 服务节点搭建
- Ethereum 使用的签名算法
- Ethereum 各套带前缀 RPC 接口的作用
- Ethereum 信标链的共识机制
- 如何质押 ETH 给信标节点
- Ethereum 底层数据结构和算法
- EVM 原理及源码
- EVM 各 op-code 的作用
- Ethereum 区块重组和回滚机制
- Ethereum 分片链(EIP4844)的原理和实现方式
- Ethereum 重要的 EIP 协议分析
- Ethereum 有哪些客户端，各客户端能实现什么功能

### 4.8 主流的 DA 项目
- EigenDA
- Celestia
- NearDA
- Anytrust
- Eip4844

DA 的实现原理及其类似，使用的技术也是类似的，例如都用到 BLS 签名算法，KZG 零知识证明算法, 纠栅码编解码。只是安全保障源不一样，Eip4844 有 Ethereum 链保证安全性，EigenDA 由 EigenLayer 重新质押协议保证安全性，安全性继承自以太坊；Celestia 和  Anytrust 的安全性由 DAC 委员会来保证。

### 4.9 Ethereum  Layer2

- Arbitrum
- Optimistim
- Scroll
- ZksyncEra
- PolygonZkEvm
- Linea
- Starknet
以上这些项目都是以太坊 Layer2 中的原创项目，吃透这些 L2 项目，绝对是 L2 界的大牛，L2 的学习要点都类似, 主要从以下这些角度去进行学习
- Rollup 模块: 数据 rollup 和证明 rollup, 数据一般 rollup 到以太坊或者其他第三方 DA，证明 rollup 到以太坊上，由以太坊上的合约进行验证。
- Sequencer: 基于 geth 改进的适配 L2 的 EVM 客户端，有的项目是单 Sequencer，有的项目是去中心化 Sequencer。
- 验证和证明系统：证明系统分为 Zk proof 和 Fraud proof 
  - ZK proof: 链下 Zk Prove 生成证明，链上 Verifier 合约验证
  - Fraud proof：链下 rollup 关键交易数据，一旦发生欺诈，链下执行找到不同的 op-code, 链上合约进行验证。
- 跨链桥：承载 L1<->L2 的资产和消息的跨链

### 4.10 Cosmos

- Cosmos 的 SDK X 目录下的各原生模块的功能和源码
- IBC 跨链通信协议
- Tendermint 项目实现原理和源码
- CosmWarsm 实现细节
- interchain-security 原理以及实现细节
- Cosmos 和 EVM 模块结合实现细节(Ethermint 项目)
- 如何基于 Cosmos 开发自己的公链项目
- 如何基于 Cosmos 开发 AppChain 项目

### 4.11 Layer3 AppChain

- 什么是 Layer3
- 市场主流的 Layer3 AppChain 是怎么做的
- 如何设计开发一条 Layer3 AppChain
- DappLink L3 AppChain 是如何实现的
  - 跨链互操作协议解决方案
  - 多重质押协议解决方案
  - AppChain 解决方案

学会以上公链项目相关的知识，足以在币圈立足，如果觉得不够，推荐学习的项目还有 Solana, Sui 和 Aptos。

## 5. L3 上项目实战

以上是从合约，公链，钱包角度出发学习需要掌握的知识，在我们整个课程体系中，我们还会做以下项目实战
- 基于 DappLink Layer3 的治理和托管模块开发保险产品
- 基于 DappLink Layer3 的交易模块开发体验和中心化交易所一致的去中心化交易所
- 基于 LinkLayer 安全质押模型的应用开发
- 基于 DappLink Layer3 游戏模块开发一道两个小游戏
- 基于 DappLink Layer3 社交模块和 Parapack 钱包开发社交应用

## 6. 课程安排

### 6.1 学习费用
- 线上课程：3000USDT/人
- 线下课程：3500USDT/人
### 6.2 开班时间
- 满 30 人即开班
### 6.3 学习周期
- 4 个月
### 6.4 线下培训地点
- 天津市西青区
  
## 7. 师资团队

Seek: 10 年区块链开发经验，目前为 DappLink 的 CTO，前 mantle 架构师，The Web3 社区核心贡献者；曾就职于 bybit, 币信, chainup, achain 等知名区块链企业项目, 熟悉以bitcoin, ethereum, cosmos, op-stack, arbitrum, polygon 和 eigenda等项目底层实现机制和项目源码。

Wennie: 5 年区块链经验, 曾就职于区块链独角兽企业和 mantle; 参与了知名联盟链和 Mantle 设计，开发和上线，有数据库内核开发经验等。

LiuTian: MPC 技术专家，曾就职于知名 web3 企业， 从 0 到 1 带领团队完成了去中心化基金带单和 MPC 托管钱开发上线， DappLink 跨链互操作协议核心开发者。

Ron: 智能合约开发专家， 拥有 10+ 年的开发经验，5 年的 web3 开发经验，带领团队从 0 到 1 开发了多款 web3 链游项目，DappLink 多重质押协议核心开发者。

如果大家感兴趣，请点击报名：
https://docs.google.com/forms/d/e/1FAIpQLSeyuqz0TCig8zHm45tNRt_lo6faxHqNDYVmKEC9DKjX5AXkoQ/viewform

## 8. 模块课程大纲

### 1.[The Web3 公链开发教程大纲](https://github.com/the-web3/course-outline/blob/main/chain/README.md)
### 2.[The Web3 区块链钱包教程大纲](https://github.com/the-web3/course-outline/blob/main/wallet/README.md)
### 3.[The Web3 智能合约开发教程大纲](https://github.com/the-web3/course-outline/blob/main/contracts/README.md)
### 4.[The Web3 区块链就业指导教程大纲](https://github.com/the-web3/course-outline/blob/main/career-guidance/README.md)

## 9.联合举办社区

- 登链社区
- OpenBuild
- MoleDao
- GCC
- 捕鲸船社区
- LXDAO
- TinTin 中文社区
- 1783DAO
- Web3Club
- Planker

  
## 10.联合举办高校链协

- 东北大学区块链协议
- 成都信息工程大学区块链协会
- 青岛大学区块链协议
- 深圳大学区块链协议
- 南通大学区块链协会
- 吉林高校区块链联盟




