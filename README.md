# 買車 × 買房財務試算

可部署於 GitHub Pages 的純前端 PWA，適合手機與電腦使用。所有輸入資料只會存放在使用者瀏覽器的 `localStorage`，不會上傳到伺服器。

## 功能

- Tesla 車價、頭期款、車貸利率與期數試算
- 充電、保險、停車、保養等持有成本
- 年薪、獎金、固定支出與投資配置
- 每年現金、台股／ETF、公司認股、儲蓄險與車貸餘額
- 房價、貸款成數、房貸利率與購屋資金缺口
- 儲存與匯出目前試算設定
- PWA：可加入手機主畫面並支援基本離線開啟

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository，例如 `finance-planner`。
2. 將本專案全部檔案上傳到 repository 根目錄。
3. 進入 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選擇 `main`，資料夾選擇 `/ (root)`，按下 Save。
6. 等候約 1～3 分鐘，GitHub 會提供公開網址：`https://你的帳號.github.io/finance-planner/`。

## 手機加入主畫面

- iPhone Safari：分享 → 加入主畫面。
- Android Chrome：選單 → 安裝應用程式／加到主畫面。

## 更新離線快取

修改網站後，請將 `sw.js` 內的 `finance-planner-v1` 改成 `finance-planner-v2`，讓已安裝裝置取得新版檔案。
