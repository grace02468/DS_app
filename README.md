# DS_app
資料結構排序法學習App，使用機型為iPad，版本為iPadOS 17。
下載後請將Pods.zips檔解壓縮，以利後續使用。

## 主要功能
* 登入系統
* 儲存使用者學習資料至雲端資料庫
* 視覺化模擬幫助學習排序法
* 練習與測驗
  
<img width="800" alt="架構圖" src="https://github.com/grace02468/DS_app/blob/main/img/3-1.png">


## Demo
### 使用者流程及詳細功能介紹
進入到App中，使用者可以進行登入或註冊，初始頁面為使用者登入頁。使用者可以選擇忘記密碼，或是進行註冊，註冊時需輸入電子信箱、使用者名稱、密碼等資料，並且若遇到不小心輸入錯誤的信箱格式、密碼長度過短...等，導致無法住的問題，也會在下方藉由顯示紅字的方式給予提醒。

<img width="300" alt="登入" src="https://github.com/grace02468/DS_app/blob/main/img/4-1-a.png"> <img width="300" alt="註冊" src="https://github.com/grace02468/DS_app/blob/main/img/4-1-b.png">

下圖為App的主頁面，可以用下方導覽列在三個頁面間進行切換，成功登入後使用者會先進入到個人頁面，左上方會顯示用戶名稱，右上方顯示獲得的星星數，中間則是顯示各個排序目前的學習進度，也可以在此登出帳號。

點選導覽列左側的書本圖示則會進入到學習頁面，在此有插入排序、計數排序、快速排序、合併排序等四種排序讓使用者學習。點選導覽列右側會進入測驗頁面，共設計五個關卡讓使用者挑戰。

<img width="250" alt="個人頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-3-a.png"> <img width="250" alt="學習頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-3-b.png"> <img width="250" alt="測驗頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-3-c.png">

在學習的部分有模擬、練習、相關程式碼、相關影片可以供使用，使用者在學習頁面點擊插入排序後，會預設先進入插入排序的模擬頁面，並且可以點選左上角，或是透過向右滑動的手勢開啟側邊選單，向左滑動則是將選單收起，選單讓使用者方便在多種學習方式之間做切換，也可以回到排序選擇頁面選擇另一種排序做學習。

而模擬頁面還有一項輔助功能，點選右上角的問號圖示，則可以跳至模擬頁面的操作說明，讓使用者能清楚明瞭的知道操作方式。

<img width="300" alt="學習初始介面" src="https://github.com/grace02468/DS_app/blob/main/img/4-4-a.png"> <img width="300" alt="學習選單" src="https://github.com/grace02468/DS_app/blob/main/img/4-4-b.png "> <img width="300" alt="模擬頁面操作說明" src="https://github.com/grace02468/DS_app/blob/main/img/4-4-c.png">

接下來將分別展示四種排序分別的模擬頁面，首先為插入排序模擬介面，以此來做主要功能上的說明。

初始進入模擬頁面，中間會顯示該排序法的簡介，下方的工具列為主要功能區，使用者可以按下「產生亂數」按鈕，在陣列中隨機產生一組數字，也可以點擊上方陣列中的格子自行輸數數值，接著按「下一步」按鈕後，會開始進行模擬，正在進行排序動作的陣列位置會用黃底或紅字標註，使用者也可以在中間看到每個步驟的文字說明，和追蹤變數數值的變化，若有漏看、不清楚的地方，亦可按「上一步」回退。

而功能列最右邊的按鈕則可以切換到虛擬碼頁面，該頁面將會同步展示陣列的變化，和該步驟對應的虛擬碼，最後，若使用者想更改陣列數值，重新進行模擬，則可按下「重置」按鈕，清除所有正在排序的數值、說明、螢光筆標記。

<img width="300" alt="插入排序-初始頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-5-a.png"> <img width="300" alt="插入排序-步驟說明" src="https://github.com/grace02468/DS_app/blob/main/img/4-5-b.png"> <img width="300" alt="插入排序-虛擬碼" src="https://github.com/grace02468/DS_app/blob/main/img/4-5-c.png">

下圖為計數排序的模擬介面展示，功能上皆與其他排序相同，差別在於排序步驟的展示上，由於在計數排序中不只一個陣列在進行運作，因此在排序過程中，畫面中間會多出另外兩個陣列，並分別顯示其數值變化。

<img width="300" alt="計數排序-初始頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-6-a.png"> <img width="300" alt="計數排序-步驟說明" src="https://github.com/grace02468/DS_app/blob/main/img/4-6-b.png"> <img width="300" alt="計數排序-虛擬碼" src="https://github.com/grace02468/DS_app/blob/main/img/4-6--c.png">

合併排序模擬介面如下圖所示，而與其他排序法不同之處在於合併排序特別需要用視覺化的圖形呈現，才能較容易理解，因此在模擬畫面能看合併排序中特有的分割、合併過程。

<img width="300" alt="合併排序-初始頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-7-a.png"> <img width="300" alt="合併排序-步驟說明" src="https://github.com/grace02468/DS_app/blob/main/img/4-7-b.png"> <img width="300" alt="合併排序-虛擬碼" src="https://github.com/grace02468/DS_app/blob/main/img/4-7-c.png">

下圖為快速排序的模擬介面展示，功能皆與其他排序相同，並且因為各個排序的原理皆不同，因此展示出來監測的變數也不太一樣(快速排序監測i、j、l、r)。

<img width="300" alt="快速排序-初始頁面" src="https://github.com/grace02468/DS_app/blob/main/img/4-8-a.png"> <img width="300" alt="快速排序-步驟說明" src="https://github.com/grace02468/DS_app/blob/main/img/4-8-b.png"> <img width="300" alt="快速排序-虛擬碼" src="https://github.com/grace02468/DS_app/blob/main/img/4-8-c.png">

在學習的部分，還有「練習」供使用者即時檢驗學習成果，在側邊選單中點擊練習，則會進入到該排序法的練習介面，題目以單選、四個選項的選擇題方式呈現，一個排序共有五題，作答完後按下「送出」鍵，即會得到作答結果，讓使用者知道答對幾題，並在完成後每題題目下方會顯示答案，幫助使用者回頭檢視自己答錯的題目。

<img width="300" alt="作答過程" src="https://github.com/grace02468/DS_app/blob/main/img/4-9-a.png"> <img width="300" alt="作答完成反饋" src="https://github.com/grace02468/DS_app/blob/main/img/4-9-b.png">

下圖透過爬蟲爬取排序相關資料的介面，首先，在程式碼部分，會從Github上爬取資料顯示，包含該程式碼作者、程式語言和在Github上獲得的星星數，點擊則會跳轉至該頁面。

另外，右上方功能可以篩選使用者想要查找的特定程式語言，有C、C++、Java、Python供使用者選擇，亦可以選擇程式碼的排序方式，包含最相關結果、星數高到低、星數低到高。使用者也可以查找排序法的相關影片來作為學習輔助。

<img width="300" alt="相關程式碼" src="https://github.com/grace02468/DS_app/blob/main/img/4-10-a.png"> <img width="300" alt="選擇程式語言" src="https://github.com/grace02468/DS_app/blob/main/img/4-10-b.png">

<img width="300" alt="選擇資料排序方式" src="https://github.com/grace02468/DS_app/blob/main/img/4-10-c.png"> <img width="300" alt="相關影片" src="https://github.com/grace02468/DS_app/blob/main/img/4-10-d.png">

測驗介面如下圖所示，共有五個關卡，題目範圍為所教的四種排序法的隨機出題，與練習一樣以選擇題方式呈現，每一關為五題，而與練習部分的差異除了題目範圍的不同，主要還有作答完成反饋的地方多了星星數的設計，讓使用者多出闖關、成就的驅動力。

沒有答對任何題目，沒有拿星;答對一、二題，拿到一顆星; 答對三、四題，拿到兩顆星;五題全對、則為三顆星拿滿。 使用者亦可返回查看錯誤題目或是重新挑戰。

<img width="300" alt="選擇關卡" src="https://github.com/grace02468/DS_app/blob/main/img/4-11-a.png"> <img width="300" alt="作答過程" src="https://github.com/grace02468/DS_app/blob/main/img/4-11-b.png">

<img width="300" alt="作答完成反饋-1" src="https://github.com/grace02468/DS_app/blob/main/img/4-11-c.png"> <img width="300" alt="作答完成反饋-2" src="https://github.com/grace02468/DS_app/blob/main/img/4-11-d.png">

## 運用技術
* Swift
* Firebase
    * Cloud Firestore
    * Firebase Hosting
    * Firebase Authentication

### 開發工具及版本
* Figma
* Xcode 15.0.1
* Swift 5.9
* Ruby 2.6.10
* CocoaPods 1.14.3
* SideMenu 6.5.0
* iPadOS 17
