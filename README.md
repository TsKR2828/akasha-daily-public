# 阿卡夏每日館報（公開鏡像）

這裡只放**館報成品 JSON**（`output/daily_YYYYMMDD.json`），每日 06:00 從私有的
akasha-rss-news 管線單向鏡像過來，供阿卡夏圖書館 PWA 的館報模組讀取。

- 內容為改寫後的館報正文，不含原始 RSS 資料與管線程式碼。
- 請勿直接改這個 repo，下次鏡像會覆蓋。

PWA 來源網址（貼進館報模組的「自訂來源網址」設定）：

```
https://raw.githubusercontent.com/TsKR2828/akasha-daily-public/main/output/
```
