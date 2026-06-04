# 馮志遠主任 · 電子名片 Virtual Card

中華基督教會基慈小學（CCC Kei Tsz Primary School）馮志遠主任的電子名片。

純靜態網頁，支援：
- 一鍵「儲存聯絡人」（下載 vCard `.vcf`）
- QR Code 掃描即加入通訊錄
- 響應式設計，手機 / 桌面皆可

## 本機預覽

直接用瀏覽器打開 `public/index.html` 即可。

## 部署到 Cloudflare Pages

```bash
npx wrangler pages deploy public --project-name=keitsz-card
```

## 內容

| 欄位 | 內容 |
| --- | --- |
| 姓名 | 馮志遠 |
| 職銜 | 主任 |
| 學校 | 中華基督教會基慈小學 |
| 電郵 | fcy@keitsz.edu.hk |
