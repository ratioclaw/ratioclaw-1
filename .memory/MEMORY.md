# Repository Memory

## Stable Context
- **資料來源**：長期記憶主要由兩個來源構成  
  1. **Shared Manual Notes**（`shared/manual.md`）— 由人類手動維護，保存穩定規則、長期決策、常見限制與 repo 習慣。  
  2. **Daily Snapshots**（`daily/*.json`）— 由 issue agents 每日彙整的 issue 狀態與跨 issue 主題。  
- **工作流程**：  
  - 所有原始資訊皆來自 GitHub Issue / Comment。  
  - `compact-memory` 工作流會讀取 `shared/manual.md` 作為長期記憶的基礎，但不會覆寫此檔。  
- **目前觀測**：過去 10 天的 Daily Snapshots 均顯示「本次整理視窗沒有可用 issue」，因此在此期間沒有新產生的跨 issue 主題、決策或標籤。  
- **已知的 repo 習慣**（來自手動筆記）  
  - 只在 `shared/manual.md` 中記錄穩定規則與決策，避免在日誌中重複 Issue 標題。  
  - 每日快照僅在有可用 Issue 時才產生跨 issue 主題與決策摘要。  

## Recent Themes
> 目前沒有可辨識的跨 issue 主題或重複出現的議題。  
> 若未來出現持續出現的主題，將在此節更新。

## Constraints
1. **資訊來源限制**  
   - 只能引用 GitHub Issue / Comment 作為原始事實。  
   - `shared/manual.md` 為唯一的手動長期記憶來源，不能被自動覆寫。  
2. **內容呈現規則**  
   - 不得直接複製 Issue 原文或標題。  
   - 必須將每日快照的重複資訊蒸餾為可重用的長期上下文。  
3. **不確定性處理**  
   - 若資訊不足或相互矛盾，必須在相應節點標註「不確定」或「缺乏資料」。  

## Open Loops
- **Issue 更新待命**：所有每日快照皆顯示「等待下一輪 issue 更新後再整理」，表示目前缺乏可供分析的 Issue。  
- **未來主
