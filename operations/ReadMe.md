# The Web3 社区--区块链运维课程大纲

## 一.课程概述
本课程大纲（Blockchain Operations）涵盖了非区块链基础运维知识以及区块链网络的部署、管理、监控和优化。通过学习本课程，学员将能够在钱包、DeFi、或公链项目的运维工作中游刃有余。

## 二.基础篇
### 1.Linux 基础运维命令
- 文件和目录操作命令
- 文件查看和编辑命令
- 权限和所有权命令
- 系统信息查看命令
- 网络操作查看命令
- 压缩和解压命令
- 不同平台的软件包管理工具

### 2.区块链基础

#### 2.1.区块链简介

- 区块链的历史和发展
- 区块链的基本概念（区块、链、节点、共识机制）
- 公有链、私有链和联盟链的区别
- 跨链技术，隐私保护
- 主流区块链平台
- 区块链节点
- 智能合约

#### 2.2.区块链应用场景

- 数字货币（如比特币、以太坊）
- 智能合约
- 供应链管理
- 数字身份和认证

#### 2.3.分布式账本技术

- 分布式账本的定义和特性
- 数据结构（区块、Merkle 树）

#### 2.4.模块化区块链

- 数据可用层
- Layer2
- Layer3
- AppChain

#### 2.5.常见的共识机制

- 工作量证明（PoW）
- 权益证明（PoS）
- 委托权益证明（DPoS）
- 实用拜占庭容错（PBFT）

#### 2.6.密码学基础

- 对称加密和非对称加密
- 密钥交换的底层实现机制
- 数字签名
- CA 证书体系

### 3. Docker
#### 3.1.Docker 基础
- Docker 的起源和基本概念
- Docker 的安装和配置
- Docker 命令行工具和常用命令

#### 3.2.Docker 镜像

- 创建和管理 Docker 镜像
- Dockerfile 编写
- 镜像仓库（如Docker Hub）的使用

#### 3.3.Docker 容器

- 容器的创建、启动、停止和删除
- 容器生命周期管理
- 容器资源限制和管理

#### 3.4.Docker 网络
- Docker网络模式（bridge、host、overlay等）
- 配置和管理容器网络
- 容器间通信

#### 3.5.Docker 存储

- 数据卷（volumes）和绑定挂载（bind mounts）
- 容器数据管理
- 持久化存储方案

#### 3.6.Docker Compose

- Docker Compose 的基本概念
- 编写 docker-compose.yml 文件
- 多容器应用的管理和编排

#### 3.7.Docker Swarm

- Docker Swarm 的基本概念
- 集群管理和服务编排
- 高可用性和负载均衡

#### 3.8.Docker 与 CI/CD

- 使用 Docker 进行持续集成和持续交付
- 与 Jenkins、GitLab CI 等工具的集成

#### 3.9.Docker 安全

- 容器安全最佳实践
- 镜像扫描和漏洞管理
- 访问控制和认证机制

### 4.Nginx

#### 4.1.Nginx 基础
- Nginx 的起源和基本概念
- Nginx 的安装和配置
- Nginx 的工作原理

#### 4.2.Nginx 配置
- 配置文件结构和指令
- 基本配置（如server块、location块）
- 配置变量和重写规则

#### 4.3.静态和动态内容处理
- 提供静态文件服务
- 配置动态内容（如PHP、Python等）的处理
- FastCGI、uWSGI和反向代理配置

#### 4.4.反向代理和负载均衡
- 反向代理的基本概念和配置
- 负载均衡算法（轮询、最少连接等）
- 健康检查和故障转移

#### 4.5.HTTPS 和 SSL/TLS
- 配置HTTPS和SSL证书
- 配置SSL/TLS参数和安全性优化
- 使用Let’s Encrypt自动获取和更新证书

#### 4.6.缓存
- 静态和动态内容缓存
- 配置代理缓存和FastCGI缓存
- 缓存策略和优化

#### 4.7.访问控制和安全
- 基本的访问控制（IP限制、用户认证）
- 配置防火墙和DDoS防护
- 安全性最佳实践

#### 4.8.日志和监控
- 配置访问日志和错误日志
- 日志格式和分析
- 监控Nginx性能和状态

#### 4.9.高可用性和扩展
- 配置高可用性Nginx集群
- 配置热备份和恢复
- 使用Nginx模块扩展功能

#### 4.10.性能优化

- 配置优化（如worker_processes、keepalive、gzip等）
- 性能调优和瓶颈分析
- 使用工具进行性能测试和监控

#### 4.11. Lua 脚本编写开发

- Lua 基本语法
- 简单 Lua 脚本开发

### 5.Apisix

#### 5.1.APISIX 基础

- APISIX 的起源和基本概念
- APISIX 的架构和组件
- 安装和配置 APISIX

#### 5.2.基本配置

- 配置文件和基础指令
- 启动和停止 APISIX
- 管理 API 和路由

#### 5.3.路由管理

- 定义和管理路由规则
- 使用路由匹配条件（如路径、方法、头部、参数等）
- 路由优先级和顺序

#### 5.4.插件系统

- 插件的基本概念和使用
- 内置插件的配置和使用（如限流、身份认证、日志记录等）
- 插件的热加载和卸载

#### 5.5.负载均衡和服务发现

- 配置负载均衡策略
- 集成服务发现（如Consul、etcd、Nacos等）
- 动态上下线和健康检查

#### 5.6.安全和认证

- 配置认证和授权（如KeyAuth、JWT、OAuth2等）
- 使用 SSL/TLS 配置 HTTPS
- 防止常见攻击（如DDoS、SQL注入等）

#### 5.7.流量管理

- 配置限流和熔断
- 配置流量镜像和A/B测试
- 请求和响应的修改

#### 5.8.日志和监控

- 配置日志记录和日志格式
- 集成监控系统（如Prometheus、Grafana等）
- 使用日志和监控进行故障排除

#### 5.9.扩展和自定义插件

- 编写自定义插件
- 插件的测试和调试
- 社区插件和市场的使用

#### 5.10.高可用性和扩展

- 配置APISIX集群和高可用性
- 数据备份和恢复
- 性能优化和调优

#### 5.11.实战案例
- 部署常见的 API 网关场景
- 与 Kubernetes 和微服务架构的集成
- 使用 APISIX 进行流量控制和治理

#### 5.12.APISIX Dashboard
- 安装和配置 APISIX Dashboard
- 使用 Dashboard 进行 API 和插件管理
- 实时监控和日志查看

### 6.Kubernetes

#### 6.1.Kubernetes 基础
- Kubernetes 的起源和基本概念
- Kubernetes 的架构和组件（如Node、Pod、Service、Deployment等）
- 安装和配置 Kubernetes 集群

#### 6.2.核心概念
- Pod 的基本概念和管理
- ReplicaSet 和 Deployment 的使用
- Service 的类型和配置（ClusterIP、NodePort、LoadBalancer）

#### 6.3.配置管理

- ConfigMap 和 Secret 的使用
- 环境变量和配置文件管理
- 配置滚动更新和回滚

#### 6.4.存储管理

- 持久化存储卷（Persistent Volume，PV）和持久化卷声明（Persistent Volume Claim，PVC）
- 存储类（StorageClass）和动态供应
- 使用外部存储（如NFS、Ceph等）

#### 6.5.网络管理

- Kubernetes 网络模型和 CNI 插件（如 Flannel、Calico等）
- 网络策略（Network Policy）配置
- Ingress 和 Ingress Controller 的使用

#### 6.6.安全性

- 配置 RBAC（基于角色的访问控制）
- 配置安全上下文（Security Context）
- 网络安全和隔离

#### 6.7.监控和日志

- 集成 Prometheus 和 Grafana 进行监控
- 使用 Elasticsearch、Fluentd 和 Kibana (EFK) 进行日志管理
- 监控 Kubernetes 集群的健康状态

#### 6.8.自动化运维

- 使用 Helm 进行应用部署和管理
- 使用 Operators 进行自动化操作
- 配置和管理 Kubernetes Jobs 和 CronJobs

#### 6.9.高可用性和扩展

- 配置高可用性 Kubernetes 集群
- 配置水平和垂直 Pod 自动伸缩（Horizontal/Vertical Pod Autoscaler）
- 配置集群自动伸缩（Cluster Autoscaler）

#### 6.10.CI/CD集成

- 使用 Jenkins、GitLab CI 等工具进行 CI/CD 集成
- 配置持续交付流水线
- 使用 Kubernetes 进行蓝绿部署和金丝雀发布

#### 6.11.实践案例

- 部署常见的应用（如数据库、Web服务器等）
- 管理微服务架构
- 解决常见问题和故障排除

#### 6.12.Kubernetes API

- 使用 kubectl 命令行工具
- 使用 Kubernetes API 进行编程
- 编写自定义控制器和操作器

### 7.Mysql

- Mysql 的安装与使用
- Mysql 基本命令
- Mysql SQL 编程语言学习
- Mysql SQL 编程实战
- Mysql 事物特性
- Mysql 分库分表实操
- Mysql 主从配置
- Mysql 集群搭建
- Mysql 灾难恢复方案
- Mysql 从 bin log 里面恢复数据实战
- Mysql 企业级项目数据迁移实战
- Mysql 性能分析实战

### 8.Postgres

- Postgres 的安装与使用
- Postgres 基本命令
- Postgres 和 Mysql SQL 异同点
- Postgres 事物特性
- Postgres 分库分表实操
- Postgres 主从配置
- Postgres 集群搭建
- Postgres 灾难恢复方案
- Postgres 企业级项目数据迁移实战
- Postgres 性能分析实战

### 9.Elasticsearch

#### 9.1.Elasticsearch基础

- Elasticsearch的起源和基本概念
- Elasticsearch的安装和配置
- 集群架构和基本组件（如节点、索引、文档等）

#### 9.2.核心概念

- 索引、类型和文档的基本概念
- 映射（Mappings）和分析（Analyzers）
- 分片（Shards）和副本（Replicas）

#### 9.3.数据操作

- 索引数据（Indexing）
- 查询数据（Querying）
- 更新和删除数据

#### 9.4.查询和过滤

- 查询 DSL（Domain Specific Language）
- 过滤和排序
- 全文搜索和结构化搜索

#### 9.5.聚合

- 基本聚合（Aggregations）和度量（Metrics）
- 嵌套聚合（Nested Aggregations）
- 管道聚合（Pipeline Aggregations）

#### 9.6.分析和映射

- 自定义分析器、分词器和过滤器
- 动态和静态映射
- 映射更新和模板

#### 9.7.性能优化

- 索引性能优化
- 查询性能优化
- 分片管理和优化

#### 9.8.监控和管理

- 使用 Kibana 监控 Elasticsearch 集群
- 使用 Elastic Stack 进行日志分析和监控
- 集群状态和健康检查

#### 9.9.安全性

- 配置 Elasticsearch 安全性（X-Pack）
- 用户和角色管理
- SSL/TLS配置

#### 9.10.数据备份和恢复

- 快照和恢复（Snapshots and Restores）
- 集群迁移和升级
- 灾难恢复方案

#### 9.11.Elasticsearch与其他工具集成

- 与 Logstash 和 Beats 集成进行日志收集
- 与 Kibana 集成进行数据可视化
- 与其他数据存储和处理工具（如Hadoop、Spark等）的集成

#### 9.12.高级主题

- 多租户架构
- 跨集群搜索
- 自定义插件和脚本

#### 9.13.实践案例

- 部署和管理实际应用中的 Elasticsearch 集群
- 使用 Elasticsearch 进行日志分析和搜索
- 解决常见问题和故障排除

## 三.进阶篇
### 1.AWS

#### 1.1.AWS 基础服务

- EC2（Elastic Compute Cloud）: 实例类型、启动、终止、配置安全组和密钥对。
- S3（Simple Storage Service）: 存储桶管理、权限配置、版本控制和生命周期管理。
- RDS（Relational Database Service）: 数据库实例管理、备份和恢复、性能优化。
- IAM（Identity and Access Management）: 用户、组、角色、权限策略的管理。

#### 1.2.网络和安全

- VPC（Virtual Private Cloud）: 子网、路由表、Internet网关、NAT网关的配置。
- 安全组和网络ACL: 安全组规则和网络ACL规则的配置和管理。

#### 1.3.自动化

- CloudFormation: 基础设施即代码的模板创建和管理。
- Terraform: 使用代码来管理 AWS 资源。
- AWS CLI 和 SDK: 使用命令行工具和编程接口管理 AWS 资源。

#### 1.4.监控和日志

- CloudWatch: 监控资源和应用程序性能、设置警报和指标。
- CloudTrail: 记录 AWS API 调用历史，用于合规性审计。
- ELK（Elasticsearch, Logstash, Kibana）或 AWS Elasticsearch Service: 日志收集和分析。

#### 1.5.备份和恢复

- AWS Backup: 集中管理和自动化备份策略。
- 快照和 AMI: EC2 实例和 EBS 卷的快照管理和恢复。

#### 1.6.高可用性和容错

- 负载均衡（ELB）: 配置和管理应用程序负载均衡器。
- Auto Scaling: 设置自动扩展策略以应对流量变化。
- 跨区域复制: 数据跨区域复制以实现灾难恢复。

#### 1.7.成本管理和优化

- AWS Cost Explorer 和 Budgets: 监控和分析成本，设置预算和警报。
- Reserved Instances 和 Savings Plans: 使用预留实例和节省计划降低成本。

#### 1.8.容器和无服务器架构

- ECS（Elastic Container Service）和 EKS（Elastic Kubernetes Service）: 容器编排和管理。
- Lambda: 无服务器计算功能管理和事件驱动架构。

### 2.阿里云
####  2.1.阿里云基础服务

- ECS（Elastic Compute Service）: 实例类型、启动、终止、配置安全组和密钥对。
- OSS（Object Storage Service）: 存储桶管理、权限配置、版本控制和生命周期管理。
- RDS（Relational Database Service）: 数据库实例管理、备份和恢复、性能优化。
- RAM（Resource Access Management）: 用户、组、角色、权限策略的管理。

#### 2.2.网络和安全

- VPC（Virtual Private Cloud）: 子网、路由表、Internet网关、NAT网关的配置。
- 安全组和网络ACL: 安全组规则和网络ACL规则的配置和管理。
- DDoS 防护: 配置和管理 DDoS 防护服务。
- WAF（Web 应用防火墙）: Web 应用防火墙的配置和管理。

#### 2.3.运维自动化

- Terraform: 使用代码来管理阿里云资源。
- Aliyun CLI 和 SDK: 使用命令行工具和编程接口管理阿里云资源。
- Resource Orchestration Service（ROS）: 基础设施即代码的模板创建和管理。

#### 2.4.监控和日志

- CloudMonitor: 监控资源和应用程序性能、设置警报和指标。
- ActionTrail: 记录阿里云 API 调用历史，用于合规性审计。
- 日志服务（Log Service）: 日志收集、存储和分析。

#### 2.5.备份和恢复

- 混合云备份（HBR）: 集中管理和自动化备份策略。
- 快照和镜像: ECS 实例和云盘的快照管理和恢复。

#### 2.6.高可用性和容错

- 负载均衡（SLB）: 配置和管理应用程序负载均衡器。
- 弹性伸缩（Auto Scaling）: 设置自动扩展策略以应对流量变化。
- 跨地域容灾: 数据跨地域复制以实现灾难恢复。

#### 2.7.成本管理和优化

- 成本分析（Cost Analysis）: 监控和分析成本，设置预算和警报。
- 预留实例和节省计划: 使用预留实例和节省计划降低成本。

#### 2.8.容器和无服务器架构

- 容器服务（Container Service for Kubernetes, ACK）: 容器编排和管理。
- 函数计算（Function Compute）: 无服务器计算功能管理和事件驱动架构。

### 3.监控和日志系统
- 如何基于业务设计一个业务监控系统
  - 💡公链监控系统
  - 💡钱包监控系统
  - 💡Defi 产品监控
- 日志系统：日志系统搭建实战

## 四. 实战篇

### 1.挖矿节点搭建

- 如何通过 Github Action 和 Hook 去监听项目版本变动与升级
- BTC 验证人节点搭建，节点监控与日常维护
- ETH 信标链验证人节点搭建，节点监控与日常维护
- Solona 验证人节点搭建，节点监控与日常维护
- Sui 验证人节点搭建，节点监控与日常维护
- Aptos 验证人节点搭建，节点监控与日常维护
- Ton 验证人节点搭建，节点监控与日常维护
- Fil 从运维开发脚本拆分代码部署提供挖坑效率

### 2.钱包节点搭建

- BTC 钱包节点搭建，节点监控与日常维护
- ETH 钱包节点(轻节点，全节点和归档节点)搭建，节点监控与日常维护
- Solona 钱包节点搭建，节点监控与日常维护
- Sui 钱包节点搭建，节点监控与日常维护
- Aptos 钱包节点搭建，节点监控与日常维护
- Ton 钱包节点搭建，节点监控与日常维护
- Tron 钱包节点搭建，节点监控与日常维护
- XRP 钱包节点搭建，节点监控与日常维护
- ADA 钱包节点搭建，节点监控与日常维护
- AVAX 钱包节点搭建，节点监控与日常维护
- Stacks 钱包节点搭建，节点监控与日常维护

### 3.DAC 委员会节点搭建

- EigenDa 节点搭建, 节点监控与日常维护
- Celestia 节点搭建, 节点监控与日常维护
- NearDa 节点搭建, 节点监控与日常维护
- EIP4844 数据归档节点搭建与日常维护
- Anytrust 节点搭建, 节点监控与日常维护

### 4.合约部署升级
- 开发 Fork 环境实战
- 合约部署实战
- 合约升级实战
- 合约运行状态监控与检测

### 5.钱包项目部署到 EKS 实战
- CloadHSM 签名机部署实战
- Tee 环境签名机部署实战
- KMS 密钥管理部署配置实战
- 钱包扫链服务部署实战

### 6.DappLink Bridge 和 Linklayer 部署到 EKS 实战

- DappLink Bridge 合约部署，合约权限转移实战
- Linklayer 合约部署，合约权限转移实战
- DappLink Bridge 和 Linklayer 链下服务部署到 EKS 实战
  - 💡Relayer 网络
  - 💡Linklayer 链下服务
  - 💡合约事件监听和 Rollup 服务部署

### 7. 将 EigenDa 部署到 EKS 实战
- EigenLayer 合约部署，合约权限转移实战
- EigenDa da-node, da-disperser, da-retriever 和 indexer 等服务部署到 EKS 实战
- DappLink Rollup 数据到 EigenDa 项目部署实战

### 8.在 EKS  环境中部署和升级  OpStack 实战
- 构建 OpStack 本地开发环境
- OpStack 一层合约部署实战
- OpStack 二层各服务启动实战
  - 💡Op-node
  - 💡Op-geth
  - 💡Op-batcher
  - 💡Op-proposer
  - 💡Op-challenger
  - 💡Op-Services
  - 💡Indexer
- 改造 OpStack Rollup 到 EigenDa 之后进行一层升级实战
- 修改 L2 预编译合约之后进行升级实战
- 基于 OPStack 的业务监控系统和日志系统搭建

## 五.重要提示
如果您对该课程感兴趣，请加微信或者 Telegram 咨询

- 微信：17720087838
- Telegram: @shijiangguo
