# Repository Memory

## Stable Context
- **資料來源**：所有可追溯的事實皆必須來自 GitHub Issue 或 Comment，手動筆記僅作為輔助說明，**不會覆寫**原始資料。  
- **手動筆記的角色**：`shared/manual.md` 用於保存 **穩定規則、長期決策、常見限制** 以及 **repo 內部慣例**，供 `compact‑memory` 工作流程讀取。  
- **Issue 取樣設定**：  
  - 只檢視最近 **30 天** 內的 Issue。  
  - 每次快照上限 **100 個** Issue。  
  - 摘要方式採用 **deterministic** 演算法。  
- **Agent 行為**：若在取樣窗口內找不到可用 Issue，Agent 會 **保留既有記憶**，不會自行產生新條目。  
- **跨 Issue 主題與決策**：只有在有足夠 Issue 形成共通主題或決策時才會被抽取，否則保持空白。  
- **更新節奏**：每日快照會在當日 21:00 左右產生，若無新 Issue，快照內容會重複「無可用 Issue」的訊息。

## Recent Themes
- **無跨 Issue 主題**：2026‑06‑20 至 2026‑06‑26 的所有快照皆未偵測到任何跨 Issue 主題。  
- **無新決策**：同期間內未出現任何跨 Issue 決策。  
- **無活躍標籤**：`Top Labels` 為 `none`，表示目前 Issue 標籤使用情況為零。

## Constraints
1. **禁止完整複製 Issue 內容**：任何記憶條目只能以摘要或概念形式呈現。  
2. **手動筆記不可被覆寫**：`shared/manual
