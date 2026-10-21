# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶維護流程**  
  - 每日由活躍的 Issue Agents 產出 snapshot，彙整當天的 Issue 狀態與跨 Issue 主題。  
  - `shared/manual.md` 為人工維護的長期記憶手冊，僅保存 **穩定規則、長期決策、常見限制與 repo 習慣**，不會被自動流程覆寫。  
  - 原始資料來源必須是 **GitHub Issue / Comment**，任何記憶條目都應以此為根據，避免直接複製完整 Issue 文字。  
- **已知的長期規則與習慣**（從手冊中抽取）  
  1. **不複製完整 Issue**：記憶條目只能概括要點，原文保留於 Issue 本身。  
  2. **手冊為唯一手動維護入口**：`shared/manual.md` 只接受人工編輯，系統不會自動修改。  
  3. **compact‑memory workflow** 會讀取手冊內容作為上下文，但不會寫回。  
  4. **Issue 限制**：每日快照僅檢視最近 30 天、最多 100 個 Issue。  
- **目前的狀態**：在最近的 7 天內，快照皆顯示「本次整理視窗沒有可用 issue」，因此沒有新增的跨 Issue 主題或決策可納入長期記憶。

## Recent Themes
- **無活躍 Issue**：
