# UserScript-Myfcu

### 主要功能

- 將MyFcu的目錄選單由icon轉變為資料夾清單
- 新增螢幕大小偵測已支援手機使用者

### 支援的瀏覽器

<table><thead><td bgcolor=GhostWhite> 作業系統</td><td bgcolor=GhostWhite>  Firefox </td><td bgcolor=GhostWhite>  Chrome </td><td bgcolor=GhostWhite>  Edge </td><td bgcolor=GhostWhite>  Safari </td></thead><tr><td bgcolor=GhostWhite> Windows</td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightPink ><center>X</center></td></tr><tr ><td bgcolor=GhostWhite>Linux</td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=PaleGoldenRod ><center>?</center></td><td bgcolor=LightPink><center>X</center></td><td bgcolor=LightPink ><center>X</center></td></tr><tr ><td bgcolor=GhostWhite>MacOS</td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightPink><center>X</center></td><td bgcolor=LightGreen ><center>O</center></td></tr><tr ><td bgcolor=GhostWhite>Android</td><td bgcolor=LightGreen ><center>O</center></td><td bgcolor=LightPink ><center>X</center></td><td bgcolor=LightPink><center>X</center></td><td bgcolor=LightPink ><center>X</center></td><tr ><td bgcolor=GhostWhite>IOS</td><td bgcolor=LightPink ><center>X</center></td><td bgcolor=LightPink ><center>X</center></td><td bgcolor=LightPink><center>X</center></td><td bgcolor=LightPink ><center>X</center></td></tr></table>
- O : 支援    X : 不支援  ? : 未實驗 

### 版本訊息
  
- Ver 0.4  

1. 修復官方版目錄也會被resize函數影響導致跑版的問題  
2. edge及Safari不吃.before()函式之問題  
3. 支援edge及Safari  
4. First Git  
  
- Ver 0.3  

1. 在螢幕解析度太低的狀況下，將會導致無法完整顯示所有選項  
2. 點擊功能後，選單不會自動關閉  
3. 支援Firefox for Android  
  
- Ver 0.2  

1. 修復連結錯誤的問題  
  
### 安裝方法  
  
1. 安裝附加元件Tampermonkey  
2. 前往以下網站安裝[腳本](http://nicky.esy.es/UserScript/Myfcu.user.js)  
3. 前往[MyFcu](http://myfcu.fcu.edu.tw)登入網站  
4. 點擊左上角選單，更改為Fcu Apps即可