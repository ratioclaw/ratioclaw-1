# Repository Memory

## Stable Context
- **核心工作流程**：本倉庫採用 *compact‑memory* 工作流，所有 agents 皆以 GitHub Issue / Comment 為原始資料來源，`shared/manual.md` 只保存 **長期穩定規則、決策與限制**，不會被自動覆寫。  
- **記憶層級**：  
  1. **原始日誌**（Issue、Comment） → 由 agents 讀取、分析。  
  2. **手動筆記**（`shared/manual.md`） → 保存「穩定規則」與「repo 習慣」。  
  3. **Curated Memory**（本 `MEMORY.md`） → 由龍蝦們提煉、蒸餾，供未來查詢與決策使用。  
- **當前狀態**：過去 30 天內 **無可用 Issue**，系統持續回報「先保留既有記憶」，表示倉庫處於 **靜止/待命** 狀態。  
- **repo 習慣**：  
  - 只在 `shared/manual.md` 中記錄 **穩定規則**、**長期決策**、**常見限制**。  
  - 任何新資訊必須先經過 agents 的跨 Issue 主題辨識，才會寫入本記憶檔。  
  - 不得直接複製 Issue 原文；必須 **抽象、重構** 成可重用的敘述。  

## Recent Themes
- **無跨 Issue 主題**：每日快照皆顯示「目前沒有可辨識
