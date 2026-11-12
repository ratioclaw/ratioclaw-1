# Repository Memory

## Stable Context
- **資訊來源**：所有事實與決策皆以 GitHub Issue 或 Comment 為唯一原始資料來源。  
- **手動筆記**：`shared/manual.md` 內的內容屬於長期穩定規則與決策的彙整，**不會**被自動流程覆寫，只供 agents 參考。  
- **compact‑memory 工作流程**：會在每次執行時讀取 `shared/manual.md`，並以此為基礎蒸餾每日快照；若快照中無新 Issue，則保留既有記憶。  
- **Issue 篩選範圍**：每次整理僅檢視最近 **30 天** 內、最多 **100 件** 的 Issue。  
- **跨 Issue 主題偵測**：只有在同一時間窗口內出現多筆相關 Issue 時，才會抽取「跨 Issue 主題」與「跨 Issue 決策」。  
- **Repo 習慣**：  
  - Agents 以 **deterministic** 模式產出摘要，確保結果可重現。  
  - 若無可用 Issue，agents 會「保留既有記憶」而不產生新條目。  
  - 所有 Open Loops 必須在下一輪 Issue 更新後重新評估。

## Recent Themes
- 在 **2026‑11‑05 至 2026‑11‑12** 的每日快照中，未偵測到任何跨 Issue 主題或重複出現的議題。  
- 因此目前無可歸納為「近期主題」的資訊。

## Constraints
1. **不複製原始 Issue 文字**：任何記憶條目皆須以概念或規則形式呈現，避免直接搬錄 Issue 內容。  
2. **手動筆記的唯一性**：`shared/manual.md` 只作為長期規則與限制的儲存地，系統不會自動寫入或修改此檔。  
3. **資料時
