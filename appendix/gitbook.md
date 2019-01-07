# 附錄-gitbook 筆記



[markdown 語法查詢](https://markdown.tw/)



### 用gitbook init 快速長出書本架構

初始有會兩個檔案

- README.md —— 關於這本書的介紹
- SUMMARY.md —— 這本書的目錄結構

構思完這本書的大綱之後(編輯summary.md)

    [楔子](README.md)
    [各種學習資源](Chapter0/資源.md)

下指令

> $ gitbook init

就可以自動依照結構生成檔案(ex: Chapter0/資源.md)

