---
id: overview
title: NEAR APIs
sidebar_label: Overview
---

查看这些可用的APIS可以帮助您在 NEAR 上构建出色应用。

## RPC API {#rpc-api}

[NEAR RPC API](/docs/api/rpc) 提供了一个简单的 JSON RPC 2.0 API 来与 NEAR 区块链交互

| API | 介绍 |
|-----|-------------|
| [Access Keys](/docs/api/rpc/access-keys) | 检索有关帐户访问密钥的信息。 |
| [Accounts / Contracts](/docs/api/rpc/contracts) | 查看有关帐户和合约的详细信息可以更好的履行合约调用。|
| [Block / Chunk](/docs/api/rpc/block-chunk) | 查询网络并获取有关特定块或块的详细信息。|
| [Gas](/docs/api/rpc/gas) | 获取特定区块或哈希的 gas 价格。 |
| [Protocol](/docs/api/rpc/protocol) | 检索当前的起源和协议配置。|
| [Network](/docs/api/rpc/network) | 返回节点和验证器的状态信息。 |
| [Transactions](/docs/api/rpc/transactions) | 发送交易并查询其状态。 |
| [Sandbox](/docs/api/rpc/sandbox) | 本地沙盒节点上的补丁状态。 |

> **Tip:** 您可以使用 [Postman](/docs/api/rpc#postman-setup), [JavaScript](/docs/api/rpc#javascript-setup), and [HTTPie](/docs/api/rpc#httpie-setup)访问 JSON RPC 2.0 端点
> .

## REST Server {#rest-server}

[NEAR REST API Server](/docs/api/rest-server/overview) 是一个允许您创建自己的与 NEAR 区块链交互的简单 REST API 服务器的项目。

| 链接                                     | 介绍                                                                                                                 |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| [CONTRACTS](/docs/api/rest-server/contracts)                              |  在 NEAR 上部署、查看和调用智能合约。    |
| [UTILS](/docs/api/rest-server/utils)                                  |    初始化账户，创建子账户，查看密钥对。                                |
| [NFTs](/docs/api/rest-server/nfts)                            |        铸造、查看和转移 NFT。                                  |
