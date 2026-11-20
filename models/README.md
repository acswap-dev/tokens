# 模型列表

站点从本目录的 `metadata.json` 自动汇总模型列表、介绍和完整参数表。env 配置资料仓库及默认合约地址。

每个模型按网络、类别和合约地址保存。只列出已有地址的模型，测试网地址不能用于主网。

## BNB 主网（56）

共 2 个模型。

| 模型及完整参数 | 类别 | 合约地址 | 版本 |
| --- | --- | --- | --- |
| [Mint 线性参与模型](./56/participation/0x7b65ab53daa1fc812e8ab0a1f9d3a67c650d3cff/metadata.json) | 募集 | `0x7b65ab53dAA1FC812E8aB0A1F9D3A67c650d3cff` | 3.0.0 |
| [BasicVault 基础金库](./56/vault/0x3f227b6fe2459cf2c6515e4e32df279b74e31d18/metadata.json) | 金库 | `0x3F227b6Fe2459cF2C6515E4E32DF279B74E31d18` | 2.0.0 |

## BNB 测试网（97）

共 4 个模型。

| 模型及完整参数 | 类别 | 合约地址 | 版本 |
| --- | --- | --- | --- |
| [Mint 线性参与模型](./97/participation/0x85bea4666160c563c85d980e6c18923080e4d340/metadata.json) | 募集 | `0x85BEA4666160c563C85D980e6C18923080E4d340` | 3.0.0 |
| [Pump 曲线参与模型](./97/participation/0xdd80d6e7a85d157ffc13f400e5e8cef4df34cf98/metadata.json) | 募集 | `0xdd80d6E7A85D157FfC13F400e5E8CeF4dF34cf98` | 1.0.0 |
| [BasicVault 基础金库](./97/vault/0x634b67fb12c2de2ba81dcccb320d4cf76bfddba1/metadata.json) | 金库 | `0x634B67fB12c2dE2Ba81dCccb320D4cf76BfDdBa1` | 2.0.0 |
| [燃烧封顶分红金库](./97/vault/0x1790271052b7f16b157f533d6ebdd2310cfb713d/metadata.json) | 金库 | `0x1790271052b7F16B157f533D6EbDD2310cFB713d` | 1.0.0 |

## 更新方式

维护各模型的 `metadata.json` 后，在站点代码仓库执行 `npm run models:publish`。模型资料和本列表在同一提交更新。
