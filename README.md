# sui-gitpod

## 1. 用githpod 打开，等待安装依赖和环境初始化

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/CreatorsDAO/gitpod-template/tree/sui-walrus)

## 2. 新建测试账户

```shell
sui client new-address ed25519
sui client faucet
```

## 3. 配置运行 walrus

必须在 client_config.yaml 同级目录下运行

```shell
walrus get-wal
walrus info
sui client balance
walrus store ./README.md
walrus read $walrus_object_id
```

## 4. 配置 site-builder 发布站点

```shell
site-builder publish ./walrus-sites/examples/snake/
```
