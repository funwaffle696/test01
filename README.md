# 簡易Git & GitHub使用
## 步驟
1. 需要的工具
 * 下載[Git](https://git-scm.com/)

2. 在Git下指令
```
cd D:\example\test01 //記得改放自己的資料夾路徑 
git init
git add .
git commit -m "做了什麼事可以打上來 ex:變更標題顏色"
```

3. 到GitHub新增數據庫

![step1](/images/step1.png "step1")

![step2](/images/step2.PNG "step2")
#### 下圖指令"origin"這個節點名稱可以自行更改,之後執行指令記得自己打了什麼就好.
![step3](/images/step3.PNG "step3")


## 之後要push就執行下面指令,記得要在對的路徑下執行
```
git add .
git commit -m "做了什麼事可以打上來 ex:變更標題顏色"
git push -u origin main
```
