# Alaya Cross-Chain Assets Operation Guide 



## Brief Introduction

<img src="Alaya Bridge Manual-EN.assets/1.png" alt="img" style="zoom: 50%;" /> 

The Alaya cross-chain assets system is a bridge for cross-chain intercommunication between Alaya assets and Ethereum assets. Users are allowed to convert Ethereum assets (including ETH and ERC20 tokens) into Alaya's ARC20 standard tokens according to the ratio of 1:1 to take advantage of Alaya's superior performance and lower cost over Ethereum to participate in distributed applications. In the future, we will continue to update the Alaya cross-chain assets system, so that more public chains can proceed with cross-chain assets intercommunication with Alaya safely, low-costly, efficiently. 

- Current Ethereum assets supporting cross-chain: **ETH, USDT** 
- Current Alaya assets supporting cross-chain: **ATP**

 

## Operation Guide



### **1.** Preparation

 (1) Install the Ethereum Chrome plug-in wallet MetaMask (https://metamask.io/), create or import the Ethereum wallet for cross-chain in the MetaMask wallet, and prepare the Ethereum asset for cross-chain. Be aware that MetaMask is connected to the “Ethereum Main Network”. 

(2) Install the Alaya Chrome plug-in wallet Samurai, click [here](https://github.com/AlayaNetwork/Samurai/releases/download/v8.0.11/samurai-chrome-8.0.11.zip) to download (Please check the [tutorial](https://github.com/AlayaNetwork/Samurai/blob/main/docs/user-manual.md) for installation help), and create or import the Alaya wallet for cross-chain in the Samurai wallet. 



### **2.** Assets Transferred in Alaya

#### 2.1 Connect Wallet 

(1)  Enter ABank (https://abank.alaya.network/), click **'Alaya Bridge'** on the left to enter the Alaya cross-chain assets page. 

(2)  On the Alaya cross-chain assets page, enter the Transfer In Alaya function operation page under the Transfer In by default, click the **[Connect Ethereum Wallet]** button. And when the MetaMask wallet is installed and opened, the MetaMask wallet will automatically pop up on the connection authorization page. Select the wallet and confirm the connection. 

<img src="Alaya Bridge Manual-EN.assets/2.png" alt="img"  /> 

 

**Other Scenarios:** 

a. If the MetaMask wallet is locked, you need to enter your wallet password to unlock it. 

b. If a wallet is not created in MetaMask, create it first. 

c. If you need to replace the connected wallet, you need to disconnect the original wallet first. Open MetaMask wallet and disconnect it according to the following two methods. Re-initiate a connection to the new wallet address after disconnection. 

Method 1: You need to operate MetaMask in the open state of the ABank window page. 

<img src="Alaya Bridge Manual-EN.assets/3.png" alt="img" style="zoom: 80%;" /> 

Method 2: In Figure 2, you can find the connected ABank and disconnect it. 

<img src="Alaya Bridge Manual-EN.assets/4-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual-EN.assets/4-2.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual-EN.assets/4-3.png" alt="img" style="zoom: 80%;" /> 

 

#### 2.2 Ethereum Assets Transferred in Alaya 

On the premise that the Ethereum-MetaMask wallet is connected successfully, Ethereum cross-chain assets can be proceeded if the ETH balance of the wallet is not 0 and the selected Ethereum cross-chain assets (currently supporting ETH, USDT, and eATP transferring from the Alaya assets into Ethereum assets) are not 0. 

(1) First select the Ethereum assets that need to be transferred to the Alaya chain, and enter the cross-chain amount of the corresponding assets (the amount should not exceed the balance of the corresponding assets while meeting the maximum and minimum risk control requirements of the assets). 

(2) Then enter the target receiving address for Alaya (the address is filled by default when the Alaya wallet is connected). 

(3) Finally, after confirming the cross-chain transaction information is correct, click the corresponding button to submit. 

- In the case of ETH, the eATP cross-chain can be submitted directly by clicking on the **[Transfer In]** button. On the pop-up MetaMask transaction confirmation page, you can customize the Gasprice to improve the speed of the transaction confirmation. Then the transaction can be submitted after confirmation. 

<img src="Alaya Bridge Manual-EN.assets/5.png" alt="img" style="zoom: 67%;" /> 

 

- In the case of USDT or other ERC20 tokens, you need to click [Approve] for authorization when proceeding with the first cross-chain assets. On the pop-up MetaMask transaction confirmation page, the authorization transaction can be submitted after confirmation. 

<img src="Alaya Bridge Manual-EN.assets/6.png" alt="img" style="zoom: 80%;" /> 

After the authorization is successful, you can click the **[Transfer In]** button to submit the cross-chain assets transaction. On the MetaMask transaction confirmation page that pops up, you can customize the Gasprice to increase the speed of transaction confirmation. Then the transaction can be submitted after confirmation. 

 

(4) After the cross-chain transaction has been submitted, the page automatically jumps into the “History” page. Note that the transaction is displayed in the History only after the chain has been confirmed on Ethereum. Due to the slow speed of Ethereum transaction confirmation, please be patient! 

<img src="Alaya Bridge Manual-EN.assets/7.png" alt="img" style="zoom: 50%;" /> 

*Note: The entire process of cross-chain assets from Ethereumto Alaya takes about 6-30 minutes. Please be patient.* 

 

(5) When the transaction status displayed in the History changes to **“Success”**, which means that the Ethereum cross-chain asset is completed, and the user can check the received assets in the corresponding Alaya receiving wallet. 

*Note: If you want to check Alaya cross-chain token assets in Samurai wallet, click **[Add Tokens]** at the Samurai Asset List, and add the corresponding token information. The token information can be obtained from the Alaya-Scan blockchain browser-tokens-token list (https://scan.alaya.network/tokens/tokenList, please identify the officially authenticated token contract).* 

<img src="Alaya Bridge Manual-EN.assets/8-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual-EN.assets/8-2.png" alt="img" style="zoom: 80%;" /> 

<img src="Alaya Bridge Manual-EN.assets/8-3.png" alt="img" style="zoom: 50%;" /><img src="Alaya Bridge Manual-EN.assets/8-4.png" alt="img" style="zoom: 50%;" /> 

 

 

 

### **3.** Assets Transferred out of Alaya 

#### 3.1 Connect Wallet

(1) Enter ABank (https://abank.alaya.network/), click **'Alaya Bridge'** on the left, and enter the Alaya cross-chain assets page. 

(2) On the Alaya cross-chain assets page, click the **[Transfer Out]** tab, to switch to the Transfer Out From Alaya function operation page, click the **[Connect Alaya Wallet]** button, and when the Samurai wallet is installed and opened, the Samurai wallet will automatically pop up the connection authorization page. Select the wallet and confirm connection. 

<img src="Alaya Bridge Manual-EN.assets/9.png" alt="img" style="zoom: 80%;" /> 

 

**Other Scenarios:** 

a. If Samurai wallet is locked, you need to enter your wallet password to unlock it. 

b. If a wallet is not created in Samurai, create it first. 

c. If you need to replace the connected wallet, you need to disconnect the original wallet first. Open Samurai wallet and disconnect it according to the following two methods. Re-initiate a connection to the new wallet address after disconnection. 

Method 1: You need to operate Samurai in the open state of the ABank window page. 

<img src="Alaya Bridge Manual-EN.assets/10.png" alt="img" style="zoom: 80%;" /> 

Method 2: In Figure 2, you can find the connected ABank and disconnect it. 

<img src="Alaya Bridge Manual-EN.assets/10-1.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual-EN.assets/10-2.png" alt="img" style="zoom: 80%;" /><img src="Alaya Bridge Manual-EN.assets/10-3.png" alt="img" style="zoom: 80%;" /> 

#### 3.2 Alaya Assets Transferred out to Ethereum

On the premise that the Alaya-Samurai wallet is connected successfully, Alaya cross-chain assets can be proceeded if the ATP balance of the wallet is not 0 and the selected Alaya cross-chain assets (currently supporting ATP, Ethereum assets aETH and aUSDT that crossed in) are not 0. 

(1) First, select the Alaya assets that need to be transferred to the Ethereum chain and enter the cross-chain amount of the corresponding assets (the amount should not exceed the balance of the corresponding assets while meeting the maximum and minimum risk control requirements of the assets). 

(2) Then enter the target receiving address for Ethereum. 

(3) Finally, after confirming the cross-chain transaction information is correct, click the **[Transfer Out]**button to submit. On the pop-up Samurai transaction confirmation page, you can customize the Gasprice to improve the speed of transaction confirmation. Then the transaction can be submitted after confirmation.

<img src="Alaya Bridge Manual-EN.assets/11.png" alt="img" style="zoom: 80%;" /> 

*In particular, it is necessary to state that: In the process of Alaya assets being transferred out to Ethereum, ETH transaction fees need to be paid out due to the execution of Ethereum cross-chain contracts. Based on the user experience, the system pays directly for the users, and the users only need to pay the corresponding numbers of cross-chain tokens assets as the Transfer Fee.* 

 

(4) After the cross-chain transaction has been submitted, the page automatically jumps into the “History” page. Notes that the transaction is displayed in the History only after the chain has been confirmed on Alaya. 

<img src="Alaya Bridge Manual-EN.assets/12.png" alt="img" style="zoom: 80%;" /> 

*Note: The entire process of cross-chain assets from Alaya to Ethereum takes about **6-30** minutes. Please be patient.* 

 

(5) When the transaction status displayed in the History changes to **“Success”**, which means that the Alaya cross-chain asset is completed, and the user can check the received assets in the corresponding Ethereum receiving wallet.  
