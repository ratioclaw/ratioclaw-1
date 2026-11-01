# Repository Memory  

## Stable Context  
- **Repository**：`ratioclaw/ratioclaw-1`。所有長期記憶皆以此 repo 為核心。  
- **資訊來源**：  
  - **GitHub Issue / Comment** 為原始事實的唯一來源。  
  - **`.memory/shared/manual.md`** 為人類手動維護的長期記憶，保存 **穩定規則、長期決策、常見限制、repo 習慣**。  
- **工作流程**：  
  - **compact‑memory workflow** 會在每次執行時讀取 `manual.md`，但 **不會覆寫**。  
  - 每日快照 (`daily/*.json`) 只負責蒐集最近 30 天內的 Issue 活動，並將跨 Issue 的主題、決策、未完成事項抽取成結構化欄位。  
- **目前狀態**：過去 7 天的每日快照皆顯示 **「本次整理視窗沒有可用 issue」**，代表近期 repo 內沒有活躍的 Issue。這是一個 **穩定的靜止狀態**，而非臨時錯誤。  
- **長期規則**（自 manual.md 推斷）：  
  1. 所有可重用的規則與決策必須寫入 `shared/manual.md`。  
  2. 任何日誌或臨時資訊只能出現在每日快照或 Issue 本身，**不會**直接寫入手動筆記。  
  3. 產出 `MEMORY.md` 時必須 **蒸餾**（distill）資訊，避免逐段複製原文。  

## Recent Themes  
- **無跨 Issue 主題**：從 2026‑10‑26 至 2026‑11‑01 的所有快照均未偵測到可辨
