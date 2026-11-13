# Repository Memory

## Stable Context
- **Repository 狀態**：截至 2026‑11‑13，`ratioclaw/ratioclaw-1` 在過去 30 天內未出現任何可用的 Issue。系統持續保留既有記憶，但未偵測到新議題或變更。  
- **記憶工作流程**：  
  - 只以 **GitHub Issue / Comment** 為原始資料來源。  
  - `compact‑memory` 工作流會讀取本手動筆記（`shared/manual.md`），但不會覆寫它。  
- **Agent 行為**：每日快照皆顯示「本次整理視窗沒有可用 issue，先保留既有記憶」，表示 agents 目前處於待命狀態，等待新 Issue 的產生或更新。  

> **不確定性**：因為缺乏任何 Issue 記錄，我們無法確認是否有隱藏的、未被 agents 捕捉的工作項目或決策。

## Recent Themes
- **無跨 Issue 主題**：最近七天（2026‑11‑07 至 2026‑11‑13）的所有快照均報告「目前沒有可辨識的跨 issue 主題」。  
- **無新決策**：同期間未出現任何跨 Issue 的決策紀錄。  

> **備註**：若未來出現臨時性或一次性的議題，請將其歸入「Open Loops」或在下一次快照中重新評估。

## Constraints
1. **資料來源限制**  
   - 只能使用 GitHub Issue 與 Comment 作為原始資訊。  
   - 不得直接複製完整 Issue 內容至本手動筆記或長期記憶檔案。  
2. **記憶更新規則**  
   - `compact‑memory` workflow 只讀取本手動筆記，不會自動覆寫。  
   - 任何新增或變更的長期規則、決策或限制必須由人類手動編輯 `shared/manual.md`。  
3. **可讀性與工程化**  
   - 本文件須保持 Markdown 結構清晰，方便 agents 程式化解析。  
   - 內容應以「龍蝦」的口吻敘述，但仍保留技術術語與關
