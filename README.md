# 沐映資金管理（GitHub Pages 版）

粉紫主題・純前端運行。功能含：VIP 權重 → 同級 FIFO、跨日生效、分單配對、自動/手動配對、CSV/JSON 匯出、備份/還原。

## 一鍵部署方式 A：GitHub Pages（推薦）
1. 到 GitHub 建立新 repository（例如 `muying`）。
2. 上傳本資料夾所有檔案（`index.html`、`404.html`、`assets/favicon.svg`、`.github/workflows/pages.yml`、`netlify.toml`、`README.md`）。
3. 進入 repo 的 **Actions** 頁籤，啟用 GitHub Actions（若提示）。
4. 推送或上傳之後，Actions 會自動執行 **pages** workflow，完成後會產生 Pages 網址（例如 `https://你的帳號.github.io/muying/`）。

> 如果你偏好手動設定：Settings → Pages → Deploy from a branch → 選 `gh-pages` 分支（workflow 會幫你建立）

## 一鍵部署方式 B：Netlify（可選）
- 點擊：

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

選你的 GitHub repo 後一路下一步即可，上線後會得到 `https://隨機名.netlify.app/` 網址。

## 使用說明
- 直接開啟網站即可使用（資料存在使用者 LocalStorage）。
- 在「系統設定」可切換 VIP 優先/FIFO、拆分單位、跨日生效規則。
- 可下載 CSV 報表與 JSON 備份；也能匯入還原。

## 注意
- 這是前端示例，沒有儲存到伺服器。若要多用戶權限、電子發票、報表與資料庫，我可以提供後端與 Docker Compose 一鍵部署。

---

© 沐映
