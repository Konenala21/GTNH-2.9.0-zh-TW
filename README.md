# GTNH 2.9.0 正式版繁體中文翻譯包

想用繁體中文玩 GTNH 2.9.0，可以直接下載這份翻譯包。這是個人整理的版本，**GTNH 2.9.0 是正式版，beta 1 指的是翻譯包**。目前已完成檔案檢查，最後一輪修改還在等遊戲內確認。

## 下載

[下載繁中翻譯包 ZIP](https://github.com/Konenala21/GTNH-2.9.0-zh-TW/releases/download/zh-tw-beta.1-for-gtnh-2.9.0/GTNH-2.9.0-zh-TW-beta1.zip)

## 安裝

1. 關閉遊戲，打開 GTNH 2.9.0 正式版實例的 `.minecraft` 資料夾。
2. 如果你自己改過繁中語言檔，先備份那些檔案。
3. 把 ZIP 裡的內容解壓到 `.minecraft`。保留原本的資料夾結構，遇到同名語言檔時覆寫。
4. 開啟遊戲，選擇「繁體中文」。

這份 ZIP 要解壓到 `.minecraft`，**不要直接放進 `resourcepacks`**。它只包含語言檔，沒有世界、NEI、個人設定、模組或伺服器資料。製作時使用的是 GTNH 2.9.0 正式版 Java 17-26 客戶端。

## 翻譯從哪裡來

主要以 GTNH 2.9.0 正式版的簡體中文翻譯為基礎，用 OpenCC `s2tw` 轉成繁體，再對照英文與原有繁中檔案修正格式、名稱和描述。部分物品名稱參考 GTNH 中文 Wiki 與 MC百科，另外修正了 157 個描述或提示文字。

目前的靜態比對涵蓋 74,947 個英文鍵，繁中缺鍵為 0。這代表文字鍵都有對應值，遊戲內字形、排版和每句譯文仍需要繼續檢查。下載包內共有 294 份語言檔，已核對路徑與 SHA256。

翻譯來源和授權資訊見 [NOTICE](NOTICE.md) 與 [LICENSE](LICENSE)。這是個人維護的翻譯包；GTNH 官方的翻譯參與方式可看[官方說明](https://www.gtnewhorizons.com/GTNH-Dev-Doc/contributing/contribute-translations/)。
