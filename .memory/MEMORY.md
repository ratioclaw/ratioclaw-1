# Repository Memory

## Stable Context
- **Issue‑driven記憶**：所有長期記憶的原始資料皆來自 GitHub **issue** 與 **comment**，這是唯一的事實來源。  
- **手動筆記的角色**：`shared/manual.md` 用於保存 **穩定規則、長期決策、常見限制、repo 習慣**，且 **不會被自動流程覆寫**。  
- **compact‑memory 工作流程**：Agents 會在每次執行時先讀取手動筆記，再根據最新的 issue 狀態產出摘要；若無可用 issue，則保留既有記憶不變。  
- **近期觀測**：從 2026‑07‑28 至 2026‑08‑03 的每日快照皆顯示「本次整理視窗沒有可用 issue」，代表 **目前 repo 中無活躍 issue**。  
- **跨 Issue 主題與決策**：在過去 30 天內未偵測到任何跨 Issue 主題或新決策。  

> **不確定性**：因為缺乏 issue 資料，我們無法確認是否真的沒有任何待處理事項，或是有隱藏/私有 issue 未被快照捕捉。

## Recent Themes
- **無重複主題**：每日快照皆未報告可辨識的跨 Issue 主題，表示近期沒有持續出現的議題。  
- **靜默期**：連續七天的快照均顯示「沒有可用 issue」，可視為 repo 正
