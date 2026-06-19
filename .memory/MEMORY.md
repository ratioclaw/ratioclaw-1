# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **資訊來源**：所有原始事實皆來自 GitHub Issue 與 Comment，這是唯一可信的資料來源。  
- **手動筆記 (`shared/manual.md`)**：  
  - 用於保存 **穩定規則、長期決策、常見限制、repo 習慣**。  
  - **不可** 直接複製完整 Issue 文字；只能抽取、濃縮後寫入長期記憶。  
  - `compact‑memory` 工作流程會 **讀取** 此手動筆記，**不會覆寫**。  
- **Issue 處理範圍**：  
  - 每次整理最多檢視 **100 個 Issue**。  
  - 只關注過去 **30 天** 內的活動。  
- **Agent 行為**：在沒有可用 Issue 時，保持現有記憶不變，等待下一輪更新。  

## Recent Themes
- **2026‑06‑13 至 2026‑06‑19**：連續七天的每日快照皆顯示「本次整理視窗沒有可用 Issue」，因此 **未偵測到任何跨 Issue 主題、決策或新標籤**。  
- **共通訊息**：所有天的報告皆為「保留既有記憶」與「等待下一輪 Issue 更新」。  

## Constraints
1. **資料唯一性**：只能以 Issue / Comment 為原
