# Repository Memory

## Stable Context
- **資料來源**：長期記憶的唯一正式來源是 GitHub Issue / Comment。所有可追溯的事實與決策必須能在 Issue 歷史中找到對應的原始紀錄。  
- **手動筆記**：`shared/manual.md` 只用來保存 **穩定規則、長期決策、常見限制** 以及 **repo 習慣**，不會被自動流程覆寫。  
- **Compact‑Memory 工作流程**：會在每次執行時讀取 `shared/manual.md`，但不會自行寫入或刪除其中的內容。  
- **Issue 整理窗口**：每日快照只會在過去 30 天內有 **可用 Issue** 時產生跨 Issue 主題與決策。若無可用 Issue，系統會保留既有記憶並等待下一輪更新。  

> **不確定性**：目前尚未在 Issue 中觀測到任何具體規則或決策，故上述「穩定」項目僅為流程層面的約定，非主人行為或業務層面的長期事實。

## Recent Themes
- **無可辨識跨 Issue 主題**：2026‑10‑01 至 2026‑10‑09 的每日快照皆顯示「目前沒有可辨識的跨 issue 主題」。  
- **持續無 Issue**：連續 9 天（含當天）皆未出現可供整理的 Issue，說明目前的開發或任務活動在 Issue 系統中處於靜止狀態。  

> **觀察**：若未來持續缺乏 Issue，可能代表：
  1. 主人暫停使用 Issue 追蹤工作；或
  2. Issue 被其他工具或平台取代。  
  需要進一步確認主人目前的工作追蹤方式。

## Constraints
1. **只能引用 Issue / Comment**：任何新增的長期記憶必須能追溯至 Issue，否則不被視為正式記錄。  
2. **手動筆記不可被自動覆寫**：`shared/manual.md` 只能由人類手動編輯，系統僅作為讀取來源。  
3. **每日快照的範圍限制**：只檢視最近 30 天內的 Issue，超出此範圍的資訊不會自動納入本記憶庫。  
4. **缺乏 Issue 時保留既有記憶**：當沒有可用 Issue 時，系統不會刪除或修改既有的 Stable Context、Constraints 或 Open Loops。  

## Open Loops
- **等待 Issue 更新**
