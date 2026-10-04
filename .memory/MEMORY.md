# Repository Memory

## Stable Context
- **目前尚未在 issue 中確立任何長期穩定規則**。  
- **長期決策**：無可供引用的跨 issue 決策紀錄。  
- **共通限制**  
  - 只有 **GitHub Issue / Comment** 被視為原始資料來源。  
  - `compact-memory` 工作流程會 **讀取** 本手動筆記，但 **不會覆寫**。  
- **Repo 習慣**：目前未有明確記錄的 agent 共同遵守的作業慣例。  

> **不確定性**：因為過去 30 天的 daily snapshots 均未捕捉到任何可用 issue，以上「穩定」項目實際上可能仍在形成中，需待未來 issue 出現後再行補充。

## Recent Themes
- **無跨 issue 主題**：最近 30 天的每日快照皆顯示「目前沒有可辨識的跨 issue 主題」。  
- **無新決策**：同樣未出現任何跨 issue 決策。  

> **觀察**：近期的資料顯示 repository 目前處於靜止或待命狀態，缺乏活躍的議題流。

## Constraints
1. **資料來源限制**  
   - 只能從 GitHub Issue 與其 Comment 中抽取資訊，其他來源（如 PR、Wiki）不被視為正式記憶來源。  
2. **手動筆記的角色**  
   - `shared/manual.md` 為 **長期記憶的手動維護檔**，僅供參考與補充，系統不會自動覆寫。  
3. **記憶蒸餾規則**  
   - 只保留 **穩定且重複出現** 的資訊；臨時或一次性出現的資訊應歸入「Open Loops」或「Recent Themes」。  
4. **Issue 數量上限**  
   - 每次快照僅檢視最近 30 天內、最多 100 個 issue。若超過此上限，可能會遺漏資訊。  

## Open Loops
- **等待 Issue 更新**：所有每日快照皆顯示「等待下一輪 issue 更新後再整理」，表示目前缺乏可
