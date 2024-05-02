# 表格
![team](hw2-1.png 'team')

# PERT圖
![PERT_team](hw2-2.png 'PERT_team')

# 甘特圖
```mermaid
gantt
    title 研究流程
    section 1
    組員分組     :a1, 2024-05-02, 1d
    section 2
    組內討論     :a2, after a1  , 7d
    section 3
    擬定主題     :a3, after a2  , 3d
    section 4
    任務分配     :a4, after a3  , 5d
    section 5
    取得硬體     :a5, after a3   ,10d
    section 6
    程式開發     :a6, after a4   ,15d
    section 7
    安裝硬體     :a7, after a5 ,25d
    section 8
    程式測試     :a8, after a6 ,60d
    section 9
    撰寫使用手冊     :a9, after a7 ,30d
    section 10
    轉換檔案    :a10,after a7  , 20d
    section 11
    系統測試     :a11,after a8 , 25d
    section 12
    使用者訓練    :a12, after a9 , 30d
    section 13
    使用者測試    :a13, after a11 , 25d
    section 14
    成果發表     :a14, after a13 ,2d
```
# 甘特圖

```mermaid
gantt
    title 甘特圖示例

    section 軟體檢測
    軟體檢測 :a1, 2024-05-02, 1d

    section 登錄申請案件基本資料
    登錄申請案件基本資料 :a2, after a1, 1d
    登錄成為會員 :a3, after a2, 1d
    政府機關 :a4, after a3, 1d
    登錄申請標章 :a6, after a2, 1d
    自我評量 :a7, after a6, 1d

    section 申請資料及Freego審核
    申請資料及Freego審核 :a8, after a7, 2d
    通過 :a9, after a8, 1d
    進行人工檢測作業 :a10, after a9, 7d

    section 檢測報告結果
    檢測報告結果 :a12, after a10, 1d
    抽檢符合 :a15, after a12, 1d
    section 抽測
    抽測 :a18, after a15, 1d

    section 結合身障者檢測
    結合身障者檢測 :a19, after a18, 1d
```



# 關鍵路徑
1>2>3>4>6>8>11>13>14
