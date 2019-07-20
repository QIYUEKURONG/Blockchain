# 区块链

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
1)开户
在本地创立一个（public key，private key）公私钥对。来源于非对称加密体系。
发送信息的视乎公钥加密，私钥解密。
加入转账的话，私钥签名，公钥验证。
产生公私钥有一个随机源。

## 数据结构