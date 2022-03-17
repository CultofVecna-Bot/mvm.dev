# 什么是 MVM 

Mixin 的愿景是希望服务更多的用户跟开发者，由于 Mixin 采用的隐私程度相同, 但是更灵活 TIP 方案来存储私钥，使得像其它链（比如 evm, eos）的开发者不能方便的使用已经技术方案。MVM 的出现解决了这方面的问题。

MVM 可以让其它网络上的开发者（几乎）不需要做任何修改部署应用，来服务 Mixin 用户，达到共赢。

# MVM 实现了哪些功能

1. 开发者可以直接把 EVM 兼容 (或 eos) 的智能合约，迁移到 MVM 上
2. 用户用转帐的操作方式，方便的使用 MVM 上的智能合约 
3. MVM 将智能合约执行后的结果，返回给用户。