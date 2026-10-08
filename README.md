# ckboomc.github.io

ckboomc YouTube 發片 app（AutoVideo 的一支，頻道 @ckboomc）的首頁與隱私權政策，供 Google OAuth 品牌驗證使用。

2026-10-08 起由 New-Moore/New-Moore.github.io 的 `ckboomc/` 子目錄搬到本 repo 根目錄，目標網域為 https://ckboomc.github.io/。

## 檔案

- `index.html`：首頁，含 `google-site-verification` meta 標記
- `privacy.html`：隱私權政策
- `style.css`：共用樣式
- `googlec4bc9eefa03ce02f.html`：Google Search Console 網站擁有權驗證檔

## 警告：不可刪除驗證檔

- `googlec4bc9eefa03ce02f.html` 不可刪除。Google 會定期回來檢查，刪掉後擁有權失效，OAuth 品牌驗證會回報「網站未註冊給您」（2026-09-26 舊站刪過一次，因此出事）。
- `index.html` 的 `google-site-verification` meta 標記是第二種驗證方法，同樣不可刪。

## 網域注意

- 網域靠 repo 位於 GitHub organization `ckboomc`（ckboomc/ckboomc.github.io）才成立（2026-10-08 已從 New-Moore 帳號轉入）。Pages 從 main 分支根目錄發布，https://ckboomc.github.io/ 已上線，驗證檔回 200。不可把 repo 轉回個人帳號或改名，否則網域與 Search Console 驗證會失效。
- 新網域在 OAuth 驗證通過前，舊站 New-Moore.github.io/ckboomc/ 不可刪。
