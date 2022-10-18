---
sidebar_position: 1
---

# Tutorial Intro

Let's discover **IDN Block in less than 5 minutes**.

## Getting Started

Get started by **subscribed our product**.

Or **try API immediately** with **[app.idnblk.xyz](https://app.idnblk.xyz)**.

## List JSON-RPC

### Get Block Number

```type=json
{
        "jsonrpc":"2.0",
        "method":"eth_blockNumber",
        "params":[],
        "id":1
}
```
### Get TransactionByHash

```type=json
{
    "jsonrpc": "2.0",
    "method": "eth_getTransactionByHash",
    "params": [
        "0xf57bd45154c6bbcf2a4be2e36ae0db40a2555422b5cb712a593d3555539ea941"
    ],
    "id": 3
}
```
### Get Balance

```type=json
{
    "jsonrpc": "2.0",
    "method": "eth_getBalance",
    "params": [
        "0xd90e3dfb935f6a878e3ae841304284b74893e710",
        "latest"
    ],
    "id": 2
}
```