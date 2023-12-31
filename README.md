# system_analysis_team11
專題名稱：請購單管理系統

組長：毛云蓁

組員：楊程宇、余欣恬、劉惠欣、蔣宗勳

專題簡介：使用primeNG的UI元件和primeflex的排版工具，為公司員工及採購部門設計一個直觀的用戶界面，當公司員工交給採購部門請購單時，採購部門能夠利用線上系統進行整合、管理，並擁有新增、讀取、編輯、刪除四種功能（CRUD），

前端進行版面及按鈕設計，確保用戶可以輕鬆管理請購單，定義欄位名稱，表格內容包含編號、申請人、公司名稱、請購部門、品名、單價、請購數量、用途、創建者、創建時間及審核狀態，每個欄位都有相應的標籤，使用戶明確知道應該輸入的資料。

後端進行資料庫建立、管理跟資料維護，處理前端請求並與資料庫進行交互，使CRUD能夠操作順利。

前端使用Angular的HttpClient模塊來發送HTTP請求到後端API端點，後端建立適當的API路由和控制器，以處理前端請求，

使CRUD操作能夠順利執行，成功接上API後，當用戶執行操作時，資料將即時更新，確保信息的即時性。

# 工作任務

| 學號 | 姓名 | 工作內容 |
|:-:| :-: | :-: |
| C110118219 | 毛云蓁 | 前端程式頁面撰寫、製作簡報 |
| C110118232 | 余欣恬 | 前端程式頁面撰寫、製作簡報 |
| C110118236 | 劉惠欣 | 前端程式頁面撰寫、製作簡報 |
| C110118242 | 蔣宗勳 | 後端資料庫程式撰寫、報告|
| C110118225 | 楊程宇 | 軟體測試、報告 |

# 專題甘特圖與PERT/CPM圖
```mermaid
gantt
    title 甘特圖

    section 2023/10/03開始
    討論主題      :a1, 2023-10-03, 8d
    工作分配      :a2,2023-10-11  , 2d
    前端程式撰寫  :a3,2023-10-13  , 37d
    後端程式撰寫   :a4,2023-10-13  , 50d
    程式測試      :a5,2023-11-27  , 10d
    程式除錯      :a6,2023-12-07  , 10d
    程式再次測試  :a7,2023-12-17 , 10d
    程式修正      :a8,2023-12-27  , 2d
    製作簡報      :a9,2023-12-29 , 3d
```

# PERT/CPM圖
![PERT](PERT.jpg "PERT")

# 至少各三項的功能性需求與非功能性需求
1. 功能性需求：
* 新增請購單（Create）：採購部門及員工皆能夠新增一個請購單，填入相應的資料，包括申請人、請購部門、品名、單價、請購數量、用途、創建者等。
* 查詢請購單（Read）：採購部門能夠查詢和瀏覽現有的請購單，員工僅能查詢自己的請購單。
* 編輯請購單（Update）：採購部門能夠編輯現有的請購單，修改相應的資料。
* 刪除請購單（Delete）：採購部門能夠刪除現有的請購單。

2. 非功能性需求：
* 直觀性：用戶界面應該是直觀的，用戶能夠輕易理解如何使用系統。
* 可用性：系统是可用的，保證高可靠性和穩定性。
* 可擴展性：系统應該能夠容易地擴展，以適應未來的需求變化。
* 實時性：對於數據更新的操作，能夠提供即時的反饋和數據更新。
* 一致性：數據在前端和後端之間保持一致，確保操作的正確性。

# 呈現功能分解圖
![功能分解](功能分解.png "功能分解")

# 寫出如ppt p20的需求分析的文字描述
### 請購單管理系統需求分析
(1) 採購部門可以藉由載入請購單管理系統申請該員工所需採購的品項、數量等。   
(2) 公司員工可以新增及讀取自己的請購申請。
(3) 採購部門依照請購單管理系審核請購申請。   
(4) 採購部門依照請購單管理系統核算金額是否會超出可用預算。   
(5) 採購部門透過請購單管理系統通知是否審核通過。   
(6) 假如請購單申請通過，採購部門則採購該申請所需的材料，公司員工可追蹤請購單狀況為已通過、審核中或是已取消。   

# 劃出使用案例圖與三個以上的使用案例說明
![使用案例](使用案例.png "使用案例")

使用案例說明
![案例1](案例1.png "案例1")
![案例2](案例2.png "案例2")
![案例3](案例3.png "案例3")
![案例4](案例4.png "案例4")

### 使用Figma劃出第一個使用案例的動態模擬畫面
![Figma](Figma管理者.png "Figma")
![Figma](Figma使用者.png "Figma")
### 系統環境圖(DFD)
![DFD](DFD.png "DFD")
### DFD 圖0
![圖0](圖0.png "圖0")

### 繪出UML類別圖(CLASS DIAGRAM)
![UML](UML.png "UML")

# 循序圖與活動圖
案例1循序圖

![循序1](循序1.png "循序1")

案例1活動圖

![活動1](活動1.png "活動1")

案例2循序圖

![循序2](循序2.png "循序2")

案例2活動圖

![活動2](活動2.png "活動2")

案例3循序圖

![循序3](循序3.png "循序3")

案例3活動圖

![活動3](活動3.png "活動3")

案例4循序圖

![循序4](循序4.png "循序4")

案例4活動圖

![活動4](活動4.png "活動4")

# 分鏡板
![1](1.png "1")
![2](2.png "2")
![3](3.png "3")
![4](4.png "4")
![5](5.png "5")
![6](6.png "6")
![7](7.png "7")
![8](8.png "8")

# 實體關係圖(ERD)
![ERD1](ERD1.png "ERD1")

# 組合實體
![組合實體](組合實體.png "組合實體")

