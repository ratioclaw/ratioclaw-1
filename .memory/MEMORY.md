# Repository Memory

## Stable Context
- **長期記憶手冊**（`shared/manual.md`）是唯一由人類手動維護、用來保存穩定規則、長期決策、常見限制與 repo 習慣的檔案。  
- **資料來源原則**：所有可追溯的事實必須來自 GitHub Issue 或 Comment；手冊本身僅作為摘要與指引，**不會**被自動覆寫。  
- **compact‑memory 工作流程**：會在每次執行時讀取 `shared/manual.md`，但不會寫入或改寫其中內容。  
- **repo 習慣**：  
  1. 只在 Issue 中記錄可執行的任務與決策。  
  2. 每日快照（`daily/*.json`）僅在有可用 Issue 時產生跨 Issue 主題與決策摘要。  
  3. 若當日無可用 Issue，快照會保留既有記憶並標示「等待下一輪 issue 更新」。

> **不確定性**：目前的快照資料未顯示任何具體 Issue、決策或跨 Issue 主題，故無法從日誌中抽取額外的穩定規則或長期決策。

## Recent Themes
- **無可辨識跨 Issue 主題**：2026‑08‑31 至 2026‑09‑06 的所有每日快照皆報告「目前沒有可辨識的跨 issue 主題」。
- **持續缺乏可用 Issue**：連續七天（含今天）皆顯示「本次整理視窗沒有可用 issue」，暗示近期 repo 內缺乏待處理或新建立的 Issue。

## Constraints
1. **資訊來源限制**  
   - 只能引用 GitHub Issue / Comment 作為事實依據；手冊僅作為摘要，不得直接複製原始 Issue 內容。  
2. **記憶更新規則**  
   - `compact-memory` 只會讀取 `shared/manual.md`，不會寫入；每日快照僅在有 Issue 時更新跨 Issue 主題與決策。  
3. **內容呈現**  
   - 本文件（`MEMORY.md`）必須是 **curated long‑term memory**，避免逐段複製原始日誌或 Issue 標題。  
4. **不確定資訊的處理
