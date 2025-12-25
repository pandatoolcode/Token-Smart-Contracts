# PandaTool 智能合约源码
PandaTool作为全网最强的一键发币平台，在EVM链拥有最多的合约机制。每一个智能合约的玩法、写法都不尽相同，现在，我们将这些合约源码统一上传至Github。尽管PandaTool的代币合约本身就是在浏览器开源的，但考虑到很多开发者获取困难的缘故，我们现在将代码放在这里，以方便各位参考学习。

需要注意的是，这个世界上没有百分百完美的代码。尤其是Solidity这种并不是非常大众的语言，可能还会有很多未知的问题存在。管PandaTool的技术团队也一直在不断的对代码进行优化，后续所有新的合约以及更新，都会同步更新在这里

## BSC合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/stardand)：标准的BEP20合约，干净、无任何功能，无权限

[holdreflection](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/holdreflection)：本币分红合约，具有持币分红本币、交易销毁等功能，无权限、合约干净

[Muti-Function](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/Muti-Function)：多功能代币，具有暂停交易、增发、设置最大持仓等多种功能

[314protocol](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/314protocol)：314协议，转账即交易，具有交易冷却防夹功能

[lpreflection](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/lpreflection)：LP分红模式，加池可以分任何代币，同时具备销毁回流、黑/白名单、交易空投等

[holdwithinviter](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/holdwithinviter)：持币复利+推荐奖励，以增发的方式实现持币生息的功能，且具有上下级

[Lpburn](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/lpburn)：底池燃烧，通过将底池内代币定时燃烧销毁，来提升币价

[holdothers](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/mint%2Bholdothers):持币分红，实现持币分其他币，如USDT、BNB、ETH等（非本币）

[lpmine](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/BSC/lpmine)：LP挖矿模式，全网独创。持有Lp开启挖矿，合约自动运行，有交易即可获得挖矿奖励

## ETH合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/ETH/stardand)：标准的ERC20合约，干净、无任何功能，无权限

## BASE合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/Base/stardand)：标准的ERC20合约，干净、无任何功能，无权限

## Arbitrum合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/Arbitrum/stardand)：标准的ERC20合约，干净、无任何功能，无权限

## Polygon合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/Polygon/stardand)：标准的ERC20合约，干净、无任何功能，无权限

## TRON合约介绍
[stardand](https://github.com/pandatoolcode/Token-Smart-Contracts/blob/main/TRON/stardand)：波场链标准的TRC20合约，干净、无任何功能，无权限

## 免责声明（Disclaimer）

[PandaTool](https://pandatool.org/)作为全网最强一键发币平台，在 GitHub 上公开的所有智能合约代码仅用于技术研究、学习与参考目的，且全部免费。但该代码完全以“现状（AS IS）”形式提供，不构成任何形式的投资建议、商业背书或安全保证。

任何个人或组织在使用、修改、部署或基于本仓库代码进行二次开发时，均需自行承担由此产生的全部法律责任与风险。PandaTool 及其志愿者团队不对因使用本代码而导致的任何直接或间接损失、违法行为、欺诈行为、合规风险或第三方纠纷承担责任。

PandaTool 明确反对并不参与任何形式的欺诈、非法融资、恶意发币、洗钱或其他违法活动。若第三方利用本仓库代码从事上述行为，该等行为与 PandaTool 无任何关联。

使用本仓库代码即视为你已充分理解并同意上述条款，并承诺遵守你所在司法辖区的相关法律法规。
