# Repository Memory

## Stable Context
- 目前的每日快照皆未偵測到任何可用的 Issue，故無法從實際工作項目中萃取出長期穩定的規則或決策。  
- 依據 **Shared Memory Manual Notes**，以下原則被視為倉庫的基礎約定（但尚未在 Issue 中具體實踐）：
  1. **資料來源**：所有事實與決策必須以 GitHub Issue 或 Comment 為唯一可信來源。  
  2. **手動筆記**：`shared/manual.md` 只作為長期記憶的補充說明，**不會被自動覆寫**。  
  3. **共同行為**：所有 agents 必須遵守 repo 的慣例與限制（具體內容需由 Issue 明確定義）。  

> **不確定性**：上述約定屬於「預設」規則，尚未在實際 Issue 中驗證或擴充，故在未來可能會有變動。

## Recent Themes
- 最近七天（2026‑06‑28 至 2026‑07‑04）的所有快照均顯示 **「沒有可用 Issue」**，因此沒有可辨識的跨 Issue 主題或重複出現的討論焦點。

## Constraints
- **資訊來源限制**：只能從 GitHub Issue / Comment 取得事實與決策，其他來源（如聊天記錄、外部文件）不被視為正式記憶。  
- **手動筆記保護**：`shared/manual.md` 會被 `compact-memory workflow` 讀取，但不會被自動寫入或覆寫。  
- **Issue 數量上限**：每日快照僅檢索最近 30 天內、最多 100 個 Issue；若超過此上限，可能會遺漏資訊。  
- **標籤依賴**：目前快照未偵測到任何 Top Labels，表示缺乏標籤驅動的分類或優先級資訊。

## Open Loops
- **等待 Issue 更新**：所有每日快照皆顯示「等待下一輪 Issue 更新後再整理」，表示目前缺乏待處理的工作項目。  
- **缺乏穩定規則**：尚未從 Issue 中抽取出具體的長期規則、決策或限制，需要在未來
