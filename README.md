# 東港創客小工具

東港 7–12 歲 Play 基地兒童創客課程用的小工具。小朋友打上名字，網站自動做成 3D 列印（STL）的檔案。

- [黑鮪魚名牌吊飾](tuna/)：打名字 → 雙色黑鮪魚吊飾 STL（0.4 mm 噴嘴，會自動檢查字的清楚度）
- [課程工具箱](courses/)：給老師用。3D 列印、雷射切割各 10 堂的課程清單，每堂有介紹、課前準備、上課用、做檔案；「機器設定」可以下載雷切插槽測試尺和 3D 間隙測試片。
- 照片雷雕／透光片和線稿轉檔小幫手合併成「創客小幫手」：[kenchen0728.github.io/maker-helper](https://kenchen0728.github.io/maker-helper/)（不限東港使用）；舊網址 `photo/` 會自動轉到創客小幫手的照片頁。課程工具箱各堂的「做檔案」也連到創客小幫手。

不用安裝，手機、平板、筆電、桌電、Chromebook 都能開。開好頁面後網路斷掉還能繼續做；要用到網路字型時才需要連線，連不到會有提示，改用電腦內建的字。

老師需要的資訊（實際大小、列印時間、換色高度、裝置資訊）在工具右上角的「老師看」。

名字不會存下來，也不會傳到別的地方。字型由 Google Fonts 提供。

© 2026 Ken Chen。歡迎免費使用，未經同意不得販售或改作販售。

字型：Noto Sans TC、Chiron GoRound TC、LXGW WenKai TC（SIL Open Font License）。三角化演算法改寫自 [earcut](https://github.com/mapbox/earcut)（ISC License）。

要退回加上課程工具箱之前的版本：用 `backup-before-courses-20261115` 分支。
要退回課程工具箱改樣式之前的版本（v1.0.0）：用 `backup-before-courses-design-20261115` 分支。
要退回加上照片雷雕之前的版本：用 `backup-before-photo-20261115` 分支。
