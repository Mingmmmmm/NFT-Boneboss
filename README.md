# Polygon NFT Trickets Project
入場Bone NightNlub驗證網站
----
### [NFT 網站連結](https://crypto0627.github.io/nft-boneboss/)

### 功能介紹:
你可以在專案網頁連結錢包、Mint NFT、查詢NFT可驗證的次數、驗證NFT、捐款。

1. 連結錢包:進入網頁後點擊畫面右上角的Connect按鈕連結您的Metamask錢包。
2. Mint NFT:連結錢包後點擊畫面Let's Mint NFT!即可花費0.02 mumbai測試幣Mint NFT。
3. 查詢NFT可驗證的次數:Mint NFT後點擊Check the remaining usage即可查詢您的NFT剩餘多少次驗證機會。
4. 驗證NFT:點擊Verify NFT Ticket驗證您購買的NFT來入場NightClub。<br>

![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/Banner.png)

#### NFT Mint顯示的交易訊息:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/mint.png)

#### NFT Check:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/check.png)

#### NFT Verify:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/verify.png)

#### NFT TokenURI_watch.png:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/TokenURI_watch.png)

#### NFT Collections:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/NFT_Collection.png)

#### Donate 我們:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/donate.png)

#### 查看公開的智能合約內容:
[NFT 合約連結](https://mumbai.polygonscan.com/address/0xB8ea8d146b880EEcd440477ecD83a1DD93F66b78#writeContract)

#### 比對TokenId:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/TokenId.png)

# 專案安裝步驟
----
## 前置作業
### 安裝及創建帳號
1. 安裝VS code、 Git、 Nodejs、 MetaMask。
2. 創建帳號 : PINATA、 ALCHEMY、 POLYSCAN、 GITHUB

### 下載專案
1. 在Terminal執行
```
git clone https://github.com/crypto0627/nft-boneboss.git
```
2. 開啟VS Code 在Terminal執行
```
npm install
npm start
```
即可看到本地端網頁
### 智能合約
1. 到PINATA上傳圖片，並創建Metadata.json檔貼上這串Opensea的格式<br>
```{
  "description": "Friendly OpenSea Creature that enjoys long swims in the ocean.", 
  "external_url": "https://openseacreatures.io/3", 
  "image": "你的IPFS圖片網址", 
  "name": "Dave Starbelly",
  "attributes": [ ... ]
}
```
2. 將Metadata.json檔上傳至PINATA
3. 在Terminal執行
```
npm install -g @remix-project/remixd
remixd -s <你的專案資料夾絕對路徑> --remix-ide https://remix.ethereum.org
```
4. 在Remix IDE點擊
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/Remix_localhost.png)
5. 編譯Boneboss.sol並選擇MetaMask部署環境(MetaMask錢包記得改成Mumbai測試網)。
6. 在Remix安裝插件FLATTENER，使用FLATTENER驗證合約，並依照POLYSCAN上指示操作驗證。
7. 驗證完後複製abi.json檔到專案資料夾 /src/utils/abi.json
8. 到ALCHEMY創建Mumbai測試網的WEB3 API，並複製API KEY到/src/utils/interact.js，複製合約地址到 /src/utils/interact.js 更改下圖的對應變數:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/contract_change.png)
改Donate位址
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/changedonate.png)
9. 在PLOYSCAN你的合約寫入Token URI，如下圖所示:
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/setTokenURI.png.png)
10. 在Github建立專案，並在此專案資料夾下執行
```
git init
git commit -m "first commit"
git branch -M main
git remote add origin 你Gihub專案的.git網址
git push -u origin main
```
11. 更改package.json的homepage改成你的Github專案網址
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/githomepage.png)
12. 到此處更改分支
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/githubpage.png)
13. 將所有檔案都部署到Github專案後執行npm run deploy
14. 完成專案部署
![image](https://github.com/crypto0627/nft-boneboss/blob/main/result_pic/complete.png)# N F T - B o n e b o s s  
 # N F T - B o n e b o s s  
 # N F T - B o n e b o s s  
 # N F T - B o n e b o s s  
 # N F T - B o n e b o s s  
 # N F T - B o n e b o s s  
 #   N F T - B o n e b o s s  
 #   N F T - B o n e b o s s  
 #   N F T - B o n e b o s s  
 #   N F T - B o n e b o s s  
 #   N F T - B o n e b o s s  
 