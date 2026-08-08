# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶來源**  
  - **手動筆記** (`shared/manual.md`) 用於保存長期穩定規則、決策與限制，**不會**被自動覆寫。  
  - **每日快照** (`daily/*.json`) 由活躍的 Issue Agents 從 GitHub Issue/Comment 中抽取，僅在有可用 Issue 時產生內容。  
- **工作流程**  
  1. Issue Agents 監控所有 Issue（包括已關閉）並在 30 天內產出每日快照。  
  2. `compact-memory` 讀取 `shared/manual.md` 以及最新的每日快照，蒸餾出長期可重用的記憶。  
  3. 若當日無可用 Issue，快照僅保留先前的記憶，並標示「等待下一輪 Issue 更新」。  
- **共通慣例**  
  - 所有規則、限制與決策必須寫在 `shared/manual.md`，以免在自動蒸餾時遺失。  
  - Issue 標題與內容僅作為原始資料來源，**不**直接寫入長期記憶文件。  
  - 每日快照的 `Open Loops` 欄位用來追蹤尚未解決的跨 Issue 事項。  

## Recent Themes
> 目前的 30 天內每日快照皆顯示 **「本次整理視窗沒有可用 issue」**，因此沒有可辨識的跨 Issue 主題、決策或新興趨勢。  
- **觀察**：連續 8 天（2026‑08‑01 至 2026‑08‑08）皆未出現任何 Issue 活動。  
- **可能意涵**：  
  - 專案暫時處於靜止或維護階段。  
  - Issue 系統可能被暫時關閉或未被正確標記為「活躍」。  

## Constraints
- **資訊完整性**：若每日快照未提供任何 Issue，必須保留既有記憶，且不得自行推測缺失的內容。  
- **避免重複**：長期記憶文件不得直接複製 Issue 標題或原始評論文字。  
- **不確定性標示**：當資訊不足或相互
