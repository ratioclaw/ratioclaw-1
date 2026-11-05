# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **目前的 Issue 狀態**：在過去 30 天內，所有每日快照皆顯示「本次整理視窗沒有可用 issue」，因此系統目前沒有可供分析的活躍議題。  
- **手動維護筆記**：  
  - 主要保存 **穩定規則、長期決策、常見限制、repo 習慣**（見 `shared/manual.md`）。  
  - 這些筆記不會被自動覆寫，僅供 agents 參考。  
- **工作流程假設**：  
  - 所有原始資訊皆來自 GitHub Issue / Comment。  
  - `compact‑memory` 工作流會讀取手動筆記，但不會自行產生或修改長期記憶條目。  

## Recent Themes
- **無跨 Issue 主題**：2026‑10‑29 至 2026‑11‑05 的每日快照皆未偵測到可辨識的跨 Issue 主題。  
- **無新決策**：同期間未出現任何跨 Issue 的決策紀錄。  
- **無標籤趨勢**：`Top Labels` 欄位皆為 `none`，顯示目前缺乏可分類的議題標記。  

## Constraints
1. **資訊來源限制**：只有在 Issue 被建立或更新時，agents 才能產生可供記憶的內容。若 Issue 數量為零，記憶庫將保持空白。  
2. **手動筆記的範圍**：`shared/manual.md` 只應包含 **概念性規則與限制**，不應直接複製 Issue 原文。  
3. **不確定性**：因缺乏活躍 Issue，無法驗證或補充任何潛在的長期規則或工作慣例。  

## Open Loops
- **等待 Issue 更新**：所有每日快照的 `Open Loops` 均寫為「等待下一輪 issue 更新後再整理」。此為唯一未解決的循環，需在未來的 Issue 活動出現時重新評估。  
- **缺乏主題與決策**：若未來出現跨 Issue 主題或決策，需即時加入 `Recent Themes` 與 `Stable Context`。  

> **備註**：目前的記憶庫主要是「空白」狀態，代表系統正處於待命階段，等待新的 Issue 流入以填充
