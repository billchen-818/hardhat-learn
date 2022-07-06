# hardhat-learn

## 创建空项目

```
npm init --yes
npm install --save-dev hardhat
npx hardhat
## 使用键盘选择“创建一个新的hardhat.config.js(Create an empty hardhat.config.js))” ，然后回车
```

## 安装插件

```
npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai

## 把
## require("@nomiclabs/hardhat-waffle");
## 添加到hardhat.config.js文件中
```

## 合约编译

```
npx hardhat compile
```

## 测试合约

```
npx hardhat test
```