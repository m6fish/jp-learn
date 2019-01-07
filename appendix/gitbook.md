# 附錄-gitbook 筆記

[這本書的位置](https://cyberbulb.gitbook.io/jp-learn/)

[gitbook 入門](https://blog.csdn.net/lu_embedded/article/details/81100704)

[markdown 語法查詢](https://markdown.tw/)



### 用gitbook init 快速長出書本架構

初始有會兩個檔案

- README.md —— 關於這本書的介紹
- SUMMARY.md —— 這本書的目錄結構

構思完這本書的大綱之後(編輯summary.md)

    [楔子](README.md)
    [各種學習資源](Chapter0/資源.md)

下指令

    $ gitbook init

就可以自動依照結構生成檔案(ex: Chapter0/資源.md)



### gitbook 預覽環境

用node.js 開啟預覽發布之後的書樣子
​    $ gitbook serve