# sui-gitpod

## 1. 用githpod 打开，等待安装依赖和环境初始化

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/CreatorsDAO/gitpod-template/tree/sui-walrus)

## 2. 新建测试账户

```shell
sui client new-address ed25519
sui client faucet
```

## 3. 配置运行 walrus

```shell
walrus --config ./walrus.yaml get-wal
walrus --config ./walrus.yaml info
sui client balance
walrus --config ./walrus.yaml store ./README.md
walrus --config ./walrus.yaml read $walrus_object_id
```
