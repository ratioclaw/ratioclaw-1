# Repository Memory

## Stable Context
- **記憶管理原則**  
  - 只保留 **穩定規則、長期決策、常見限制** 以及 **repo 共同習慣**，不直接複製 Issue 原文。  
  - 所有原始資訊皆來自 GitHub Issue / Comment，`shared/manual.md` 只作為手動維護的摘要。  
  - `compact‑memory` 工作流程會讀取本檔案，但不會覆寫它。  

- **Repo 工作慣例**  
  - 每日快照 (`daily/*.json`) 會從過去 30 天內的 Issue 中抽取跨 Issue 主題、決策與未完成事項。  
  - 若快照期間 **沒有可用 Issue**，則保留既有記憶，不產生新內容。  
  - 「Open Loops」欄位用於追蹤尚未解決的議題，待下一輪 Issue 更新後再處理。  

- **資訊可信度**  
  - 目前 **未觀測到任何跨 Issue 主題或決策**，因此無法建立長期規則或模式。  
  - 所有已知資訊皆來自 `shared/manual.md`，其內容被視為 **穩定且可信**。

## Recent Themes
- **缺乏 Issue 活動**：2026‑05‑27 至 2026‑06‑02 的每日快照皆顯示「本次整理視窗沒有可用 issue」，說明近期 repo 內沒有新 Issue 或現有 Issue 已被關閉。  
- **無跨 Issue 主題**：每一天的「Cross‑Issue Themes」皆為「目前沒有可辨識的跨 issue 主題」。  
- **無新決策**：每日的「Decisions」欄位皆為空。  

> **註**：上述主題僅反映最近 7 天的觀測結果，未必代表未來會持續缺乏活動。

## Constraints
1. **資料來源限制**  
   - 只能引用 Issue / Comment 作為原始事實來源；`shared/manual.md` 只能作為摘要。  
2. **內容編寫規則**  
   - 不得逐段複製原始 Issue 文字。  
   - 必須將重複出現的資訊 **蒸餾** 成可重用的長期記憶，而非原始日誌。  
3. **更新機制**  
   - 只有在有新 Issue 出現或現有 Issue 產生變化時，才會在本檔案中加入或
