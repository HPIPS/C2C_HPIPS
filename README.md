# C2C_HPIPS

构建去中心化C2C区块链商城，开发环境Ubuntu 16.04

# 配置智能合约的开发环境

 1.安装git 
 
 sudo apt-get install git 
 
 如果在安装git时出现E：Package 'git' has no installation candidate错误提示，只需使用以下命令代替即可
 
 sudo apt-get install git-core
 
 2.安装NodeJS
 
 sudo apt-get install curl
 
 curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
 
 sudo apt-get install -y nodejs
 
 3.安装solc
 
 sudo npm install -g solc
 
注意：终端中输入solc命令返回一个出错信息。这是因为solc只是一个程序集，如果我们想要在终端中使用solc程序编译智能合约，则需要安装solc-cli，这是solc的命令行界面使用下面安装方法：
 
 sudo npm install -g solc-cli
 
 sudo npm install -g solc solc-cli --save-dev
 
 
 4.安装testrpc
 
 sudo npm install -g ethereumjs-testrpc
 
 
 5.安装truffle
 
 sudo npm install -g truffle
 
  truffle init
 
 6.安装ganache-cli
 
 sudo npm install -g ganache-cli
 # 下载webpack模板
 
 truffle unbox webpack
 
 如果下载不了，可以使用
 
 

