# EVCharge 網站

EVCharge（公路旅誌）iOS App 的公開頁面，由 GitHub Pages 提供。

| 檔案 | 用途 |
|---|---|
| `index.html` | 首頁 |
| `privacy.html` | 隱私權政策（**App Store 送審填寫的網址就是這頁**） |
| `privacy.md` | 同一份政策的 Markdown 版本，方便閱讀與改寫 |
| `.nojekyll` | 停用 Jekyll，讓 GitHub Pages 直接照原樣提供這些檔案 |

## 網址

<https://ccwesp.github.io/evcharge/privacy.html>

App 內的付費牆會連到這個網址（`EVCharge/Features/Settings/PaywallView.swift`）。
**改網址時兩邊都要改**，否則 App 會連到 404，送審會被退件。

## 改了政策內容要做什麼

1. 同時更新 `privacy.html` 與 `privacy.md`（兩份內容要一致）
2. 把兩份的「最後更新」日期改成當天
3. commit + push，GitHub Pages 約一到兩分鐘後生效
4. 用瀏覽器實際開一次確認
