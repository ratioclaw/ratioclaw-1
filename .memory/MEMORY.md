# Repository Memory

## Stable Context
- **記憶流程**：本倉庫的長期記憶由兩大來源構成  
  1. **Shared Manual Notes**（手動維護）— 用於保存穩定規則、長期決策、常見限制與 repo 習慣。  
  2. **Daily Snapshots**（自動彙整）— 由每日活躍的 issue agents 產出，僅在有可用 issue 時才會填充內容。  
- **資料來源原則**：所有可追溯的事實必須來自 GitHub Issue / Comment；手動筆記不會被自動覆寫，只作為補充。  
- **Issue‑Driven 記憶**：目前 30 天內的 Issue 列表皆為空，故每日快照皆只保留「既有記憶」而未產生新資訊。  
- **跨 Issue 主題偵測**：在無 Issue 的情況下，系統無法辨識跨 Issue 主題或產生決策。  
- **Repo 習慣**：  
  - 每日自動產生 `daily/YYYY-MM-DD.json` 快照。  
  - 快照格式固定，包含 Agent Activity、Cross‑Issue Themes、Decisions、Open Loops、Top Labels。  
  - 若快照內無可用 Issue，會以「先保留既有記憶」作為占位說明。  

## Recent Themes
> 目前 2026‑07‑31 至 2026‑08‑07 的所有快照皆未偵測到任何跨 Issue 主題或重複出現的議題。  
> 因此 **近期主題** 為 **「無」**，即系統處於靜默狀態，等待新 Issue 的出現。

## Constraints
1. **資訊來源限制**：只能引用 Issue / Comment 作為事實依據；手動筆記僅作為補充說明，不能直接當作決策依據。  
2. **避免重複**：不應將原始 Issue 標題或內容逐段複製到本文件；必須以摘要或規則形式呈現。  
3. **不確定資訊標示**：若某資訊僅在單一天出現且未形成穩定事實，必須放入「Open Loops」或標註為不確定。  
4. **更新頻率**：每日快照若持續無 Issue，則本長期記
