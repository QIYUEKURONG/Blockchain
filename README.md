# 介绍了一些关于区块链的知识

## 密码学原理

A.1.Hash碰撞(collision resistance)
X!=Y
h(X)=H(Y)
2.hash函数的计算过程是单向的不可逆的(hiding)
X------>(X)
这两者共同实现(数字签名)digital commitment
H(X || nonce)
注意：比特币还有第三个性质。
puzzle friendly（不可预测的）
H（block header）<=target------------->工作量证明proof of work

B.比特币中用到的哈希函数是SHA-256（Secure Hash Algorithm）

