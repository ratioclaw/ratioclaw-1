# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶架構**：本倉庫的長期記憶全由 **GitHub Issue** 與 **Issue Comment** 作為原始資料來源，透過每日一次的 *issue agents* 產出 JSON 快照，並由 **compact‑memory workflow** 讀取與整理。  
- **每日快照規則**  
  - 只檢視最近 **30 天**、最多 **100 件** Issue。  
  - 產出內容包括：Agent Activity、Cross‑Issue Themes、Decisions、Open Loops、Top Labels。  
  - 若當日無可用 Issue，快照會保留既有記憶並標示「沒有可用 issue」。  
- **手動筆記 (`shared/manual.md`)** 為唯一的 **長期穩定規則** 儲存處，內容包括：  
  - 放置 **穩定規則、長期決策、常見限制、repo 習慣**。  
  - **不** 直接複製 Issue 原文。  
  - 只作為 *compact‑memory* 的參考，不會被自動覆寫。  
- **目前狀態**：過去 30 天內 **無任何 Issue** 被標記為可用，所有每日快照皆回報「先保留既有記憶」。因此，除手動筆記外，沒有新增的跨 Issue 主題或決策可供蒸餾。

## Recent Themes
- **無跨 Issue 主題**：2026‑09
