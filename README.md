## 流程
安装node

`npx hardhat init`
写合约... 
- 部署合约
npx hardhat run ./deploy.js --network localhost

vite：vue开发的一个前台工具

`npx create-vite@latest frontend`
`cd frontend`
`npm\yarn\pnpm install`
`npm install @web3-react/core`
`npm install @web3-react/metamask`
`npm install eventemitter3`
`npm install @ethersproject/contracts`

hardhat 配置
networks
 network_name:{
    ...xxx
 }


# ERC20

hardhat wallet

ERC20：两个API

approve
transferForm

初始化合约，给A、B两个账号分别分配7个、3个代币
A：7
B：3
ddd 

1. a账户初始有10个代币
2. a给b的账户转3个币

3. 切换到A的账户，授权B账户可以从A的账户转3个代币
4. 切换到B的账户上，从A里面转3个代币到B账户

5. A有4个代币，B有6个代币

前台合约交互

- react写hook
- 钱包provider


uniswap v1
https://github.com/Uniswap/v1-contracts/blob/master/contracts/uniswap_exchange.vy
