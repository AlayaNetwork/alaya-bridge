# Alaya资产跨链操作指南

[EN](https://github.com/AlayaNetwork/alaya-bridge/blob/master/docs/Alaya%20Bridge%20Manual-EN/Alaya%20Bridge%20Manual-EN.md) l **[CN](#)**


## 简介

<img src="Alaya Bridge Manual.assets/1.png" alt="img" style="zoom: 50%;" /> 

Alaya资产跨链系统是Alaya资产与Ethereum资产跨链互通的桥梁通道。允许用户将Ethereum资产（包含ETH和ERC20代币）1:1转换成Alaya的ARC20标准代币，以便利用Alaya相对于以太坊的更优性能和更低成本的优势，参与到分布式应用中。未来我们将不断更新Alaya资产跨链系统，使得更多的公链能够安全，低成本，高效率的与Alaya进行资产跨链互通。

- 当前支持跨链的Ethereum资产：**ETH，USDT**
- 当前支持跨链的Alaya资产：**ATP**

 

## 操作指南



### **1.** 准备工作

（1）安装Ethereum Chrome浏览器插件钱包MetaMask（https://metamask.io/），在MetaMask钱包内创建或导入用于跨链的Ethereum钱包，并准备跨链的Ethereum资产。注意确认MetaMask连接的是“以太坊主网络”。

（2）安装Alaya Chrome浏览器插件钱包Samurai，[点此下载](https://github.com/AlayaNetwork/Samurai/releases/download/v8.0.11/samurai-chrome-8.0.11.zip)（如需安装帮助，请查看此[教程](https://github.com/AlayaNetwork/Samurai/blob/main/docs/user-manual.md)），在Samurai钱包内创建或导入用于跨链的Alaya钱包。

 

### **2.** 资产跨入Alaya

#### 2.1 连接钱包

（1）进入ABank（https://abank.alaya.network/），点击左侧 **‘Alaya Bridge’** 菜单，进入Alaya资产跨链页面。

（2）在Alaya资产跨链页面，默认进入Transfer In 标签下的 Transfer In Alaya 功能操作页，点击**【Connect Ethereum Wallet】**按钮，在MetaMask钱包已安装并开启时，MetaMask钱包会自动弹出连接授权页面，选择钱包-确认连接即可。

<img src="Alaya Bridge Manual.assets/2.png" alt="img"  /> 

 

其他场景说明：

a. 如果MetaMask钱包已锁定，需要先输入钱包密码解锁。

b. 如果MetaMask内未创建钱包，请先创建。

c. 如果需要更换连接的钱包，需要先断开原钱包的连接。打开MetaMask钱包，根据下图两个方法断开连接。断开后重新发起新钱包地址的连接。

方法一：需要在ABank窗口页面打开状态下操作MetaMask。

<img src="Alaya Bridge Manual.assets/3.png" alt="img" style="zoom: 80%;" /> 

方法二：在图2中，找到已连接的ABank进行断开即可。

<img src="Alaya Bridge Manual.assets/4-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual.assets/4-2.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual.assets/4-3.png" alt="img" style="zoom: 80%;" /> 

 

#### 2.2 Ethereum资产跨入到Alaya

在Ethereum-MetaMask钱包连接成功的前提下，如果钱包ETH余额不为0且选择的Ethereum跨链资产(当前支持ETH，USDT，以及Alaya资产跨到Ethereum的eATP)不为0时，则可进行Ethereum资产跨链。

（1）首先选择需要跨链到Alaya链的Ethereum资产，并输入对应资产的跨链金额（金额不能超过对应资产余额，同时需满足该资产的最大最小值风控要求）。

（2）然后输入Alaya的目标接收地址（在Alaya钱包已连接状态时，默认填充该地址）。

（3）最后在确认跨链交易信息无误后，点击对应按钮提交。

- 如果是ETH，eATP跨链则可直接点击**【Transfer In】**按钮提交，在弹出的MetaMask交易确认页面，可自定义设置Gasprice提高交易确认速度，确认即可完成交易提交。

<img src="Alaya Bridge Manual.assets/5.png" alt="img" style="zoom: 67%;" /> 

 

- 如果是USDT或其他ERC20代币，在首次资产跨链时，需要点击**【Approve】**进行授权，在弹出的MetaMask交易确认页，确认即可提交授权交易。

<img src="Alaya Bridge Manual.assets/6.png" alt="img" style="zoom: 80%;" /> 

在授权成功后，即可操作点击**【Transfer In】**按钮提交资产跨链交易。在弹出的MetaMask交易确认页面，可自定义设置Gasprice提高交易确认速度，确认即可完成交易提交。

 

（4）跨链交易提交后，页面自动跳转进入“历史记录” 页面，注意交易只有在Ethereum上确认上链后，记录才会显示在历史记录中。由于以太坊交易确认速度缓慢，请耐心等待！

<img src="Alaya Bridge Manual.assets/7.png" alt="img" style="zoom: 50%;" /> 

*注意：整个Ethereum资产跨链到Alaya过程大概需要6~30分钟，请耐心等待。*

 

（5）当显示在历史记录列表中的交易状态变为 **“Success”** 时，即表示该笔Ethereum资产跨链完成，用户可以在对应Alaya接收钱包处查看到对应接收到的资产。

注：如需在Samurai钱包内查看Alaya跨链通证资产，在Samurai资产列表处，点击**【添加代币】**，将对应代币通证信息添加进入即可。代币通证信息可从Alaya-Scan区块链浏览器-令牌-令牌列表(https://scan.alaya.network/tokens/tokenList，请认准官方认证的令牌合约)处获取。

<img src="Alaya Bridge Manual.assets/8-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual.assets/8-2.png" alt="img" style="zoom: 80%;" /> 

<img src="Alaya Bridge Manual.assets/8-3.png" alt="img" style="zoom: 50%;" /><img src="Alaya Bridge Manual.assets/8-4.png" alt="img" style="zoom: 50%;" /> 

 

 

 

### **3.** 资产跨出Alaya

#### 3.1 连接钱包

（1）进入ABank（https://abank.alaya.network/），点击左侧 **‘Alaya Bridge’** 菜单，进入Alaya资产跨链页面。

（2）在Alaya资产跨链页面，点击**【Transfer Out】**标签，切换到Transfer Out From Alaya功能操作页，点击**【Connect Alaya Wallet】**按钮，在Samurai钱包已安装并开启状态下，Samurai钱包会自动弹出连接授权页面，选择钱包-确认连接即可。

<img src="Alaya Bridge Manual.assets/9.png" alt="img" style="zoom: 80%;" /> 

 

其他场景说明：

a. 如果Samurai钱包已锁定，需要输入钱包密码解锁。

b. 如果Samurai内未创建钱包，请先创建。

c. 如果需要更换连接的钱包，需要先断开原钱包的连接。打开Samurai钱包，根据下图两个方法指引断开连接。断开后重新发起新钱包地址的连接。

方法一：需要在ABank窗口页面打开状态下操作Samurai。

<img src="Alaya Bridge Manual.assets/10.png" alt="img" style="zoom: 80%;" /> 

方法二：在图2中，找到已连接的ABank进行断开即可。

<img src="Alaya Bridge Manual.assets/10-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual.assets/10-2.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual.assets/10-3.png" alt="img" style="zoom: 80%;" /> 

#### 3.2 Alaya资产跨出至Ethereum

在Alaya-Samurai钱包连接成功的前提下，如果钱包ATP余额不为0且选择的Alaya跨链资产（当前支持ATP，以及跨入的Ethereum资产aETH、aUSDT）不为0时，则可进行Alaya资产跨链。

（1）首先选择需要跨链到Ethereum链的Alaya资产，并输入对应资产的跨链金额（金额不能超过对应资产余额，同时需满足该资产的最大最小值风控要求）。

（2）然后输入Ethereum的目标接收地址，用于接收跨至Ethereum的资产。

（3）最后在确认跨链交易信息无误后，点击 **【Transfer Out】**按钮提交。在弹出的Samurai交易确认页面，可自定义设置Gasprice来提高交易确认速度，确认即可完成交易提交。

<img src="Alaya Bridge Manual.assets/11.png" alt="img" style="zoom: 80%;" /> 

*需要特别说明的是：在Alaya资产跨出至Ethereum的过程中，由于需要执行Ethereum跨链合约而支出ETH交易手续费，基于用户体验考虑，系统直接为用户支付，用户只需要支付对应跨链通证资产数量作为手续费（Transfer Fee）即可。*

 

（4）跨链交易提交后，页面自动跳转进入“历史记录” 页面，注意交易只有在Alaya上完成确认上链后，记录才会显示在历史记录列表中。

<img src="Alaya Bridge Manual.assets/12.png" alt="img" style="zoom: 80%;" /> 

*注意：整个Alaya资产跨链到Ethereum过程大概需要 **6~30**分钟，请耐心等待。*

 

（5）当显示在历史记录列表中的交易状态变为 **"Success"** 时，即表示该笔Alaya资产跨链完成，用户可以在对应Ethereum接收钱包处查看到对应接收到的资产。

 

 

 