<div align="center"><a href="https://itunes.apple.com/app/id1345822611" target="_blank"><img src="https://kimieno.github.io/ios.pitt/images/app_store_badge.png" width="150" height="55" ></a></div>
<div align="center">或是<a href="https://testflight.apple.com/join/TDrhSSs0" target="_blank">加入測試計畫</a></div>

# 操作手冊
[登入畫面](#登入畫面)  
[連線畫面](#連線畫面)  
[主畫面](#主畫面)  
[工具列](#工具列)  
[看板列表](#看板列表)  
[看板選項](#看板選項)  
[最愛看板排序](#最愛看板排序)  
[信件列表](#信件列表)  
[信件選項](#信件選項)  
[話題功能](#話題功能)  
[最新消息/延燒話題](#最新消息/延燒話題)  
[延燒話題選項](#延燒話題選項)  
[延燒話題設定](#延燒話題設定)  
[編輯隱藏看板](#編輯隱藏看板)  
[關注話題選項](#關注話題選項)  
[關注話題設定](#關注話題設定)  
[編輯關注看板](#編輯關注看板)  
[閱讀紀錄](#閱讀紀錄)  
[閱讀紀錄分類](#閱讀紀錄分類)  
[閱讀紀錄顯示方式](#閱讀紀錄顯示方式)  
[刪除閱讀紀錄](#刪除閱讀紀錄)  

# FAQ
[PTT 與 PiTT 的關係](#PTT與PiTT的關係)  
[PTT 的連線方式](#PTT的連線方式)  
[無法登入](#無法登入)  
[連線緩慢](#連線緩慢)  

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
顯示目前連線狀態

4. ### 連線位址
預設為 SSH 連線，可為 ptt.cc 或以 ip 顯示（供中國使用者連線用，可在設定內調整，ptt.cc 無法在中國連線），WebSocket 連線為 ws.ptt.cc，目前為實驗性質。  
**由於 SSH 連線使用人數較多，在熱門時段會因為 PTT 站台連線數限制導致常常出現連線超時或失敗等問題，因此雖然 WebSocket 尚在實驗階段，但還是建議使用此連線方式以便快速登入。**  
  
#### [返回頁首](#操作手冊) 

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
  
#### [返回頁首](#操作手冊) 

## 工具列

![Image of Toolbar Page](https://kimieno.github.io/ios.pitt/images/toolbar.png)

1. ### 展開工具列
點擊後可展開工具列，可進行排序與其他操作

2. ### 使用功能
點擊按鈕可直接使用該功能

3. ### 拖曳排序
長按按鈕可啟動排序，放置於常駐區塊將依照排序顯示於工具列，上限為七個按鈕，放置於其他區塊則不會顯示於工具列  
  
#### [返回頁首](#操作手冊) 

## 看板列表

看板列表包含最愛看板、熱門看板及子目錄

![Image of Boards Page](https://kimieno.github.io/ios.pitt/images/boards_page.png)

1. ### 看板項目
點擊進入看板、目錄，長按顯示看板選項，此處選項會依據分頁類型（如：最愛看板、熱門看板）或看板類型（目錄、是否加入最愛等等）而有所不同，前方的圓圈分別為藍色代表有新進文章未讀，灰色代表沒有新進文章未讀。

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
  
#### [返回頁首](#操作手冊) 

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
  
#### [返回頁首](#操作手冊) 

## 最愛看板排序

![Image of Favorite_Sorting Page 1](https://kimieno.github.io/ios.pitt/images/favorite_sorting_1.png)  
![Image of Favorite_Sorting Page 2](https://kimieno.github.io/ios.pitt/images/favorite_sorting_2.png)

1. ### 自訂看板位置
點擊後將可自訂任意看板位置，以拖曳方式操作，設定後無法復原。

2. ### 依照看板名稱排序
設定後無法復原

3. ### 依照看板分類排序
設定後無法復原

4. ### 拖曳看板
長按此按鈕啟動拖曳功能，可將看板位置移動至任意位置，右方序號將維持至儲存設定，以便恢復原位。

5. ### 完成排序
點擊後儲存排序結果。  
  
#### [返回頁首](#操作手冊) 

## 信件列表

![Image of Mail Page](https://kimieno.github.io/ios.pitt/images/mail_page.png)  

1. ### 信件項目
點擊閱讀信件，長按顯示信件選項，前方的圖示為藍色代表未讀、灰色代表已讀、回覆圖示代表已回信。

2. ### 信件標題
寄件備份的標題前方將保留回信對象ID

3. ### 信件日期/作者
若此處為系統信件將無法回信，若為轉寄信件則顯示轉寄者的ID，而非轉寄內容作者的ID。
因此轉寄信件直接回信為回信給轉寄者，若需回信給內容作者可使用內容介面的「寫信給作者」。

4. ### 信件序號/狀態
此處將顯示信件為已讀、未讀、M標記、已回信等狀態，信件項目前方的圓圈及已回覆圖示皆以此為基準顯示。  
  
#### [返回頁首](#操作手冊) 

## 信件選項

![Image of Mail Options](https://kimieno.github.io/ios.pitt/images/mail_options.png)  

1. ### 查詢作者資訊
點擊後將顯示作者資訊頁面。

2. ### 刪除信件
點擊後將刪除信件，確認視窗確定刪除後無法還原。

3. ### 轉寄信件
點擊後將顯示轉寄頁面，可將信件轉寄給其他鄉民或外部信箱。

4. ### M起來/取消M
點擊後將信件標記，標記的信件可避免意外被刪除，再使用一次此功能取消標記。

5. ### 封鎖
將寄件者加入封鎖名單，所有文章、信件、推文、水球以及話題皆會被封鎖，被封鎖的項目會顯示為淡化項目  
此處之所以不完全隱藏項目，是為避免造成 App 有刻意隱藏特定資訊的疑慮  
所有封鎖項目皆可隨時查閱或解除封鎖

6. ### 好鄉民
將寄件者加入好鄉民名單，推文前方將顯示愛心圖示，同時加入封鎖及好鄉民表示為超級好友，除了不會顯示為封鎖狀態外，推文前方將顯示特殊圖示。

7. ### 檢舉信件
將違規信件通報給管理者，由於信件只能到 Violation 看板檢舉，點擊後將僅顯示提示。

8. ### 自爆
很恐怖，不要問

9. ### 召喚神龍
集齊七顆龍珠即可使用

10. ### 毫無意義的按鈕
按了就知道  
  
#### [返回頁首](#操作手冊) 

## 話題功能

![Image of Topics](https://kimieno.github.io/ios.pitt/images/topics.png)  

PiTT 有三大話題功能，取向各有不同，囊括 PTT 最具有討論度的話題  

*最新消息 - 全站最新發佈文章，篩選出具有成為延燒話題潛力的話題
*延燒話題 - 全站熱門文章，篩選出最具有討論度的文章
*關注話題 - 僅顯示有興趣的看板話題，或是使用**聚焦**功能顯示單一看板的所有話題，可設定為最新消息模式（預設）或延燒話題模式而顯示不同話題。    
  
#### [返回頁首](#操作手冊) 

## 最新消息/延燒話題

![Image of New_and Hot_Topics](https://kimieno.github.io/ios.pitt/images/new_n_hot_topic.png)

1. ### 文章標題
此文章的標題

2. ### 推文數
此文章的推文數，由於 PTT 在搜尋模式下的推文數顯示行為較特殊，不會顯示一般文章列表看到的推文數，因此有時會顯示為沒有推文是屬於正常狀態。

3. ### 看板
此文章所在看板

4. ### 日期/作者
此文章發佈的日期與作者  
  
#### [返回頁首](#操作手冊) 

## 延燒話題選項

與最新消息共用相同選項

![Image of Topic Options](https://kimieno.github.io/ios.pitt/images/topic_options.png) 

1. ### 暫時隱藏此話題
點擊後將暫時隱藏話題，直到下次重新啟動 App 為止

2. ### 永久隱藏此話題
點擊後將永久隱藏此話題所在看板的所有文章，也可以在展開工具列後使用設定功能進入封鎖看板頁面編輯

3. ### 加入關注話題看板
點擊後會將此看板加入關注話題，若已加入則會顯示為移除選項

4. ### 查詢作者資訊
點擊後將顯示作者資訊頁

5. ### 搜尋同標題文章
點擊後將以此文章標題搜尋文章，PTT 站台的搜尋為「包含」方式，因此若出現類似標題也屬於正常結果

6. ### 搜尋同作者文章
點擊後將以此作者搜尋文章，PTT 站台的搜尋為「包含」方式，因此若出現其他作者文章也屬於正常結果

7. ### 封鎖
將作者加入封鎖名單，所有文章、信件、推文、水球以及話題皆會被封鎖，被封鎖的項目會顯示為淡化項目  
此處之所以不完全隱藏項目，是為避免造成 App 有刻意隱藏特定資訊的疑慮  
所有封鎖項目皆可隨時查閱或解除封鎖

8. ### 好鄉民
將作者加入好鄉民名單，推文前方將顯示愛心圖示，同時加入封鎖及好鄉民表示為超級好友，除了不會顯示為封鎖狀態外，推文前方將顯示特殊圖示。

9. ### 檢舉文章
將違規文章通報給板主，將會自動進入發信頁面並自動帶入檢舉表單與檢舉對象，若文章所在看板沒有板主將僅顯示至 Violation 看板檢舉提示。  
  
#### [返回頁首](#操作手冊) 

## 延燒話題設定

![Image of Topic Settings Options](https://kimieno.github.io/ios.pitt/images/topic_settings.png) 

1. ### 設定
點擊後開啟話題設定選項

2. ### 切換排序
共有兩種排序方式，依話題熱門度排序以及依話題新鮮度排序

3. ### 編輯隱藏看板
點擊後進入編輯隱藏看板頁面，可新增隱藏看板或刪除隱藏看板  
  
#### [返回頁首](#操作手冊) 

## 編輯隱藏看板

與最新消息共用設定

![Image of Hidden Boards_Page](https://kimieno.github.io/ios.pitt/images/hidden_boards.png) 

1. ### 輸入看板
可一次輸入多個看板同時新增，以換行方式分隔各看板，不分大小寫

2. ### 新增看板
點擊後新增隱藏看板

3. ### 隱藏看板
隱藏看板列表

4. ### 編輯看板
點擊後開始編輯看板，可解除看板話題隱藏狀態

5. ### 完成編輯
點擊後完成編輯，離開此頁面後才會正式儲存編輯結果

6. ### 刪除看板
點擊後刪除此看板  
  
#### [返回頁首](#操作手冊) 

## 關注話題選項

![Image of Subscribed Topic_Options_Page](https://kimieno.github.io/ios.pitt/images/subs_options.png) 

1. ### 暫時隱藏此話題
點擊後將暫時隱藏話題，直到下次重新啟動 App 為止

2. ### 從關注話題看板移除
點擊後將此看板自關注話題看板移除，講不再顯示此看板文章

3. ### 查詢作者資訊
點擊後將顯示作者資訊頁

4. ### 搜尋同標題文章
點擊後將以此文章標題搜尋文章，PTT 站台的搜尋為「包含」方式，因此若出現類似標題也屬於正常結果

5. ### 搜尋同作者文章
點擊後將以此作者搜尋文章，PTT 站台的搜尋為「包含」方式，因此若出現其他作者文章也屬於正常結果

6. ### 封鎖
將作者加入封鎖名單，所有文章、信件、推文、水球以及話題皆會被封鎖，被封鎖的項目會顯示為淡化項目  
此處之所以不完全隱藏項目，是為避免造成 App 有刻意隱藏特定資訊的疑慮  
所有封鎖項目皆可隨時查閱或解除封鎖

7. ### 好鄉民
將作者加入好鄉民名單，推文前方將顯示愛心圖示，同時加入封鎖及好鄉民表示為超級好友，除了不會顯示為封鎖狀態外，推文前方將顯示特殊圖示。

8. ### 檢舉文章
將違規文章通報給板主，將會自動進入發信頁面並自動帶入檢舉表單與檢舉對象，若文章所在看板沒有板主將僅顯示至 Violation 看板檢舉提示。  
  
#### [返回頁首](#操作手冊) 

## 關注話題設定

![Image of Subscribed Topic_Settings_Page](https://kimieno.github.io/ios.pitt/images/subs_settings.png) 

1. ### 聚焦看板
點擊後將顯示目前已加入關注話題的所有看板，可隨意切換至任意看板瀏覽所有話題。

2. ### 設定
點擊後開啟關注話題設定選項

3. ### 切換排序
有預設模式（最新消息模式）與延燒話題模式兩種排序，話題篩選模式也各不相同。

4. ### 切換群組顯示
開啟後將以編輯隱藏看板頁面內的排序顯示看板話題，並在各看板依照第三點設定的排序顯示，關閉後則與延燒話題及最新消息相同，顯示話題的原始排序

5. ### 編輯關注看板
點擊後進入編輯關注看板頁面，可新增或刪除看板，也可以在此調整看板顯示排序。  
  
#### [返回頁首](#操作手冊) 

## 編輯關注看板

![Image of Subs Boards_Page](https://kimieno.github.io/ios.pitt/images/subs_boards.png) 

1. ### 輸入看板
可一次輸入多個看板同時新增，以換行方式分隔各看板，不分大小寫

2. ### 新增看板
點擊後新增隱藏看板

3. ### 關注看板
關注看板列表

4. ### 編輯看板
點擊後開始編輯看板，可解除看板話題隱藏狀態

5. ### 完成編輯
點擊後完成編輯，離開此頁面後才會正式儲存編輯結果

6. ### 刪除看板
點擊後刪除此看板

7. ### 拖曳排序
若開啟群組設定，將會以此處的排序顯示看板話題，各看板內的話題再依照話題排序顯示  
  
#### [返回頁首](#操作手冊) 

## 閱讀紀錄

![Image of Subs Records_Page](https://kimieno.github.io/ios.pitt/images/records_page.png) 

1. ### 切換分類
點擊後顯示分類選單，共有五種分類  

*所有文章 - 目前登入帳號的所有閱讀紀錄，包含我的文章及已推文
*我的文章 - 目前登入帳號發文紀錄（需閱讀過才會紀錄）
*已推文 - 目前登入帳號推過文的文章記錄
*稍後閱讀 - 目前登入帳號加入稍後閱讀的文章
*追蹤文章 - 目前追蹤的文章

2. ### 搜尋紀錄
依據看板名稱、作者、標題等資訊搜尋紀錄

3. ### 標題
文章標題

4. ### 日期/作者/看板
文章發佈日期、作者及所在看板

5. ### 收錄日期
加入閱讀紀錄的日期

6. ### 編輯模式
開啟編輯模式，可刪除紀錄

7. ### 設定
開啟設定，可調整列表顯示方式

8. ### 刪除所有紀錄
可一次刪除所有紀錄

#### [返回頁首](#操作手冊) 
