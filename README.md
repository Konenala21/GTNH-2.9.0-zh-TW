# GTNH 2.9.0 正式版繁體中文翻譯包

適用於 **GT: New Horizons 2.9.0 正式版** 的繁體中文語言覆蓋包。

目前的翻譯包版本為 **beta 1**。測試版指翻譯包的驗證狀態，GTNH 2.9.0 本身是正式版。

## 下載與安裝

1. 從 [Releases](../../releases) 下載 `GTNH-2.9.0-繁體中文獨立翻譯包-2026-11-02.zip`。
2. 關閉遊戲，備份現有的繁中語言檔。
3. 將 ZIP 內容解壓到 GTNH 2.9.0 正式版實例的 `.minecraft` 目錄。保留 ZIP 內的目錄結構，讓 `config/txloader/...` 等檔案回到原路徑。
4. 在遊戲內選擇「繁體中文」。

這是 TXLoader 與外部語言檔的覆蓋包，不能直接放進 `resourcepacks`。封包只含語言檔，不含世界、NEI、個人設定、模組 JAR 或伺服器資料。此版以 GTNH 2.9.0 Java 17-26 客戶端的已安裝檔案製作。

## 內容與驗證

- 294 份繁中語言檔，保留原始相對路徑。
- 以 GTNH 2.9.0 正式版簡中為主要來源，使用 OpenCC `s2tw` 轉為繁體，並保留人工核對的既有名稱與格式。另修正 157 個描述或提示鍵。
- 本機英文鍵比對：74,947 個唯一英文鍵，繁中缺鍵 0 個。簡中缺鍵但繁中有鍵的項目為 2,218 個。
- ZIP 已通過 CRC 與逐檔 SHA256 驗證。可用 Release 的 SHA256 值檢查下載檔。
- 最後一輪描述修改尚未完成遊戲內顯示驗證。零缺鍵只代表靜態鍵覆蓋，不代表所有譯文與排版都正確。

## 來源與授權

繁中內容主要根據 [GTNH-Translations](https://github.com/GTNewHorizons/GTNH-Translations) 的簡中翻譯及 GTNH 2.9.0 已安裝語言檔整理，並參考 [GTNH 中文 Wiki](https://gtnh.huijiwiki.com/) 和 [MC百科](https://www.mcmod.cn/) 核對部分名稱與提示。OpenCC 用於字形轉換。

本倉庫是個人維護的翻譯覆蓋包。翻譯來源及授權資訊見 [NOTICE.md](NOTICE.md) 和 [LICENSE](LICENSE)。GTNH 官方翻譯貢獻流程見 [官方說明](https://www.gtnewhorizons.com/GTNH-Dev-Doc/contributing/contribute-translations/)。
