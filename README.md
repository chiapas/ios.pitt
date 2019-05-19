<div align="center"><a href="https://itunes.apple.com/app/id1345822611"><img src="https://kimieno.github.io/ios.pitt/images/app_store_badge.png" width="150" height="55" ></a></div>
<div align="center">或是<a href="https://testflight.apple.com/join/TDrhSSs0">加入測試計畫</a></div>

# 操作手冊
[登入畫面](#登入畫面)  
[連線畫面](#連線畫面)  
[主畫面](#主畫面)  
[工具列](#工具列)  
[看板列表](#看板列表)  
[看板選項](#看板選項)

## 登入畫面

![Image of Login Page](https://kimieno.github.io/ios.pitt/images/login_page.png)

1. ### 關於 
點擊後進入關於頁面，可查看 PiTT 更新紀錄等資訊

2. ### 無法連線疑難排解
點擊後開啟疑難排解步驟，可簡單排除無法連線的問題

3. ### 設定
點擊後進入設定頁面，可調整連線方式、自動預覽圖片、調色盤、字型大小、封鎖名單等各項設定

4. ### 快速登入選單
在設定頁開啟此功能後將顯示此按鈕，可快速選擇帳號登入

5. ### 帳號
輸入帳號，12個字元以下英數字，不含空白及符號，若使用其他 App 註冊時可能因為該 App 未提醒此帳號格式導致輸入過長帳號而不自知，此時請輸入前 12 字元即可登入

6. ### 密碼
輸入密碼，8個字元以下任意字元

7. ### 登入按鈕
點擊後登入，若使用**長按**方法將在登入時自動將此帳號設為主帳號，下次啟動 PiTT 時將自動以主帳號登入，也可在登入後開啟主選單點擊帳號設定/取消主帳號

## 連線畫面

![Image of Connecting Page](https://kimieno.github.io/ios.pitt/images/connecting_page.png)

1. ### 站台負載
顯示目前站台負載情形  

  * 檢測 - 取得狀態中
  * 順暢 - 可快速登入
  * 正常 - 可正常登入
  * 緩慢 - 稍難登入
  * 衰弱 - 較難登入，常出現連線超時或無法連線
  * 掛了 - 無法登入，站台出現問題  
  
2. ### 無法連線疑難排解
點擊後開啟疑難排解步驟，可簡單排除無法連線的問題

3. ### 目前狀態
顯示目前連線狀態

4. ### 連線位址
預設為 SSH 連線，可為 ptt.cc 或以 ip 顯示（供中國使用者連線用，可在設定內調整，ptt.cc 無法在中國連線），WebSocket 連線為 ws.ptt.cc，目前為實驗性質。  
**由於 SSH 連線使用人數較多，在熱門時段會因為 PTT 站台連線數限制導致常常出現連線超時或失敗等問題，因此雖然 WebSocket 尚在實驗階段，但還是建議使用此連線方式以便快速登入。**

## 主畫面

共有十種分頁，分別為最愛看板、熱門看板、分類看板、鄉民信箱、最新消息、延燒話題、關注話題、閱讀紀錄、最近造訪、鄉民名冊  
可在主選單 - 設定 - 設定分頁顯示與順序內調整首頁、排序與分頁開關。

![Image of Page View Page](https://kimieno.github.io/ios.pitt/images/page_view.png)

1. ### 首頁
點擊項目可設定為首頁，項目左方將有突顯標記，登入後將首先顯示此分頁

2. ### 編輯
點擊後可開始編輯排序與分頁開關

3. ### 調整排序、分頁開關
可拖曳各項目調整顯示排序，或放置於「關閉」區塊，此區塊內的分頁將不會顯示，至少需啟用三個以上的分頁。  

4. ### 完成編輯
點擊後完成分頁編輯，將在下次啟動 app 時生效。

## 工具列

![Image of Toolbar Page](https://kimieno.github.io/ios.pitt/images/toolbar.png)

1. ### 展開工具列
點擊後可展開工具列，可進行排序與其他操作

2. ### 使用功能
點擊按鈕可直接使用該功能

3. ### 拖曳排序
長按按鈕可啟動排序，放置於常駐區塊將依照排序顯示於工具列，上限為七個按鈕，放置於其他區塊則不會顯示於工具列

## 看板列表

看板列表包含最愛看板、熱門看板及子目錄

![Image of Boards Page](https://kimieno.github.io/ios.pitt/images/boards_page.png)

1. ### 看板項目
點擊進入看板、目錄，長按顯示看板選項，此處選項會依據分頁類型（如：最愛看板、熱門看板）或看板類型（目錄、是否加入最愛等等）而有所不同

2. ### 看板類型
顯示看板類型，可為目錄或連結以及此看板是否加入最愛，最愛看板根目錄所有看板皆已加入最愛，因此一律不顯示最愛圖示，但子目錄則會顯示此圖示

3. ### 看板名稱
可以此名稱搜尋看板

4. ### 看板分類
此看板所屬分類

5. ### 看板描述
又稱板標，由板主修改。

6. ### 看板人氣
原始 PTT 站台人氣超過一千人後僅以「爆!」字加上顏色顯示，為協助新警察了解人氣代表意義，轉為數字顯示，數字顏色為原始 PTT 站台設定的人氣顏色  
原始站台顯示方式如以下所示：  

  * 白色 - 九十九人以下看板，並直接顯示人氣  
  * 亮白色 - 一百人以上看板，並顯示為 HOT  
  * 亮白色 - 一千人以上看板，並顯示為 爆!（以下顯示文字皆相同）  
  * 亮紅色 - 兩千人以上看板  
  * 亮藍色 - 五千人以上看板  
  * 亮青色 - 一萬人以上看板
  * 亮綠色 - 三萬人以上看板
  * 亮黃色 - 六萬人以上看板
  * 亮紫色 - 十萬人以上看板  

7. ### 看板序號
此看板在此頁面的序號，經由排序可改變，也可在特定排序功能內輸入序號調整排序

8. ### 搜尋看板
點擊後可搜尋看板，可使用看板名稱或關鍵字（板標）搜尋

9. ### 重新整理
點擊後重新整理最愛看板

10. ### 寄信
點擊後進入信件編輯頁面

11. ### 主選單
點擊後開啟主選單

## 看板選項

長按看板項目後顯示的看板操作項目

![Image of Boards_Options Page](https://kimieno.github.io/ios.pitt/images/board_options.png)

1. ### 新增/移除最愛
將看板加入/移除最愛看板，已加入最愛僅顯示移除選項，反之亦然  
若在子目錄顯示的情況下加入/移除最愛，則僅會異動此目錄內的看板

2. ### 全部已讀
將看板內所有文章設為已讀

3. ### 全部未讀
將看板內所有文章設為未讀

4. ### 加入/移除關注話題看板
關注後的看板文章將顯示於關注話題分頁，已加入關注話題將僅顯示移除選項，反之亦然

5. ### 調整看板排序
點擊後將顯示排序選項，有自訂排序、依照看板名稱排序以及依照看板分類排序三種方式
