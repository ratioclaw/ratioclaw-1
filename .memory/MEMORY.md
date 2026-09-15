# Repository Memory

## Stable Context
- 目前的日誌與快照皆未檢測到任何可用的 Issue，故無法抽取長期穩定規則或決策。  
- 依照 **Shared Memory Manual Notes**，以下原則被視為倉庫的基礎約定，屬於永久性限制而非臨時資訊：  
  1. **GitHub Issue / Comment 為唯一原始資料來源**，所有事實與決策必須追溯至此。  
  2. **shared/manual.md** 為手動維護的長期記憶檔案，系統會讀取但不會覆寫此檔。  
  3. 任何 **compact‑memory workflow** 必須尊重上述兩點，避免直接複製 Issue 原文。  

> **不確定性**：除上述元規則外，缺乏實際 Issue 內容，使得目前無法確定任何業務流程、工作習慣或技術決策屬於「穩定」狀態。

## Recent Themes
- 最近 30 天（2026‑09‑09 至 2026‑09‑15）的所有 Daily Snapshots 均報告 **「本次整理視窗沒有可用 issue」**，因此未出現可辨識的跨 Issue 主題或重複出現的討論焦點。  
- 由於缺乏資料，**近期主題** 目前只能說是「無活動」或「等待新 Issue」的狀態。

## Constraints
1. **資料來源限制**  
   - 只能從 GitHub Issue / Comment 取得事實與決策。  
   - 任何非 Issue 的文字（如聊天紀錄、即時訊息）不應被視為正式記憶來源。  

2. **手動筆記限制**  
   - `shared/manual.md` 只能由人類手動編輯，系統不會自動寫入或覆寫。  
   - 內容應聚焦於「穩定規則、長期決策、常見限制、repo 習慣」等長期可重用資訊。  

3. **記憶蒸餾流程**  
   - `compact-memory workflow` 必須在抽取資訊時避免逐段複製原始 Issue 文字，需以摘要或規則形式呈現。  

## Open Loops
- **Issue 更新待命**：所有 Daily Snapshots 均顯示「等待下一輪 issue 更新後再整理」，因此目前的未完成事項
