# EVCharge 網站

EVCharge（公路旅誌）iOS App 的公開頁面，由 GitHub Pages 提供。

| 檔案 | 用途 |
|---|---|
| `index.html` | 首頁 |
| `privacy.html` | 隱私權政策（**App Store Connect 的「隱私權政策網址」填這頁**） |
| `support.html` | 支援與常見問題（**App Store Connect 的「支援網址」填這頁，必填**） |
| `privacy.md` | 同一份政策的 Markdown 版本，方便閱讀與改寫 |
| `.nojekyll` | 停用 Jekyll，讓 GitHub Pages 直接照原樣提供這些檔案 |

## 網址

| App Store Connect 欄位 | 網址 |
|---|---|
| 隱私權政策網址 | <https://ccwesp.github.io/evcharge/privacy.html> |
| 支援網址（必填） | <https://ccwesp.github.io/evcharge/support.html> |

⚠️ **這個 repo 不可以改成 private，也不能刪。** 一改 private，GitHub Pages 立刻下線，
App Store 上的兩個網址同時變 404。

App 內的付費牆會連到這個網址（`EVCharge/Features/Settings/PaywallView.swift`）。
**改網址時兩邊都要改**，否則 App 會連到 404，送審會被退件。

## 改了政策內容要做什麼

1. 同時更新 `privacy.html` 與 `privacy.md`（兩份內容要一致）
2. 把兩份的「最後更新」日期改成當天
3. commit + push，GitHub Pages 約一到兩分鐘後生效
4. 用瀏覽器實際開一次確認
