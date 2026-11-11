# Luma Pocket

Luma Pocket 的 App 支援與隱私權政策網站，以 GitHub Pages 發布（純靜態 HTML，無建置步驟）。

- 網站：https://autumn192837465.github.io/luma-pocket/
- 通用隱私權政策（所有 App 共用）：https://autumn192837465.github.io/luma-pocket/privacy.html

## 已收錄的 App

| App | 套件名稱 | 隱私權政策 | 使用支援 |
| --- | --- | --- | --- |
| QR 掃描製作器（Quick QR: Scan & Create） | `com.kinopistudio.quickqr` | `privacy.html#quick-qr` | `quick-qr/support.html` |

## 新增 App

所有 App 共用 `privacy.html`，Google Play 與 App Store 的隱私權政策網址都填 `https://autumn192837465.github.io/luma-pocket/privacy.html`。新增 App 時：

1. 在 `privacy.html`「二、適用的應用程式」與英文版「2. Apps covered」各加一組 App 名稱（中英文）、套件名稱、平台。
2. 在「七、各 App 補充說明」與英文版「7. App-specific details」各加一個 `<section>`（檔案內有註解範本），寫明實際使用的權限、本機資料與第三方服務。用了廣告、Firebase、分析或付費 SDK 時，一定要寫出傳送哪些資料給誰，並和 Play「資料安全性」及 App Store 隱私標籤一致。
3. 更新頁首的「更新日期」。
4. 需要支援頁時，建立 `<app>/support.html`，並在 `index.html` 加一張 App 卡片。

Google Play 會比對政策中的開發人員名稱（Luma Pocket）、App 名稱與套件名稱是否和商店資訊一致，不一致會被判定「應用程式或開發人員詳細資料不相符」。

`quick-qr/privacy.html` 只是轉址到 `privacy.html#quick-qr`，保留給舊連結使用。
