# UserScript-Myfcu

### 主要功能
- 將MyFcu的目錄選單由icon轉變為資料夾清單
- 重新依照功能進行分類
- 提供快速搜尋功能
- 新增螢幕大小偵測已支援手機使用者

### 支援的瀏覽器

|作業系統|Firefox|Chrome|Edge|Safari|
|:------|:-----:|:-----:|:---:|:---:|
|Windows|O|O|O|O|
|Linux|O|O|X|X|
|MacOS|O|O|X|O|
|Android|O|X|X|X|
|IOS|X|X|X|X|

- O : 支援    X : 不支援  ? : 未實驗 

### 安裝方法(Firefox、Chrome、Edge、Safari、Opera Next)
1. 安裝附加元件[Tampermonkey](https://tampermonkey.net/)  
2. 前往以下網站安裝[腳本](https://nicky.tw/UserScript/Myfcu.user.js)  
3. 前往[MyFcu](https://myfcu.fcu.edu.tw)登入網站  
4. 點擊左上角選單，更改為Fcu Apps即可

### 版本訊息
- Ver 1.3
  1. 修復寬度溢位時會導致第二行重疊的問題
  2. 修復v1.2因連結失效無法顯示圖示的問題
  3. 移除ajax時無法被設定的header
  4. 將重算視窗大小的副程式獨立出來，而非複製貼上

- Ver 1.2
  1. 修正搜尋欄缺少部分按鈕問題
  2. 更新下載點為https
  3. 取消Firefox、Firefox for Android附加元件化
  4. 移除Firefox、Edge、Chrome附加元件包

- Ver 1.1
  1. 修正官方API更換格式問題

- Ver 1.0(Firefox add-on v1.1)
  1. 修正API與官方對接
  2. 新增搜尋功能
  3. 取消網頁注入，改為事件綁定
  4. 取消動態修改頁面，改為頁面切換
  5. 完成Firefox、Firefox for Android附加元件化
  6. 於課表與學習平台新增課堂打卡功能

- Ver 0.5  
  1. 新增載入中提視窗

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
  
### 開發環境與套件
- Windows 10
- Notepad++
- Firefox 65.0.2
- Tampermonkey 4.8.x
- JQuary 3.3.1

### 教學資源
- [Firefox Add-on doc(MDN Web docs)](https://developer.mozilla.org/zh-TW/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)
- [Tampermonkey文檔](https://tampermonkey.net/documentation.php?ext=dhdg&show=dhdg)
- [JQuary API](https://api.jquery.com/)
  
### 開發人員
- 夢之旋律(陳琮斌)

### 版權訊息
UserScript-Myfcu、MyTreeFcu 版權所有 (C) 2019 Dream_Rhythm

本程式是自由軟體，您可以遵照自由軟體基金會 ( Free Software Foundation ) 出版的 GNU 通用公共許可證條款 ( GNU General Public License ) 第三版來修改和重新發佈這一程式，或者自由選擇使用任何更新的版本。

發佈這一程式的目的是希望它有用，但沒有任何擔保。甚至沒有適合特定目的而隱含的擔保。更詳細的情況請參閱 GNU 通用公共許可證。
