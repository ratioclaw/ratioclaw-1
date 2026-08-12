# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶管理流程**  
  - 每日由各 issue agent 產出 snapshot，彙整當天的 issue 狀態與跨 issue 主題。  
  - `shared/manual.md` 為人工維護的長期記憶檔，僅保存 **穩定規則、長期決策、常見限制與 repo 習慣**，不會被自動覆寫。  
  - 原始資料來源必須是 **GitHub Issue / Comment**，手動筆記僅作為摘要與指引。  
- **目前狀態**（截至 2026‑08‑12）  
  - 最近 30 天內 **無可用 issue**，因此每日 snapshot 均顯示「先保留既有記憶」。  
  - 沒有跨 issue 主題、決策或標籤被辨識。  

## Recent Themes
- **無新出現的跨 issue 主題**：過去一週的所有 snapshot 均未偵測到重複或持續的議題。  
- **持續的空白狀態**：每日皆報告「本次整理視窗沒有可用 issue」，顯示目前工作項目暫停或尚未產生。  

## Constraints
1. **資料來源限制**  
   - 只能從 GitHub Issue / Comment 抽取資訊，任何手動筆記皆屬二次摘要，不能直接作為事實依據。  
2. **手動筆記的使用規則**  
   - `shared/manual.md` 只保留 **穩定規則、長期決策、常見限制與 repo 習慣**，不應複製完整 issue 原文。  
   - 這份手動筆記會被 `compact-memory` 工作流讀取，但不會被自動覆寫。  
3. **記憶更新頻率**  
   - 每日 snapshot 只在有可用 issue 時才會產生新資訊，否則保留既有記憶。  
4. **資訊不確定性**  
   - 若某件事僅在最新一天短暫出現且未形成穩定事實，必須歸入 **Open Loops**，不列為穩定規則。  

## Open Loops
- **等待下一輪 issue 更新**：所有每日 snapshot 均指出「等待下一輪 issue 更新後再
