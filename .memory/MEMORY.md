# Repository Memory

## Stable Context
- **長期規則**  
  - 只將 **GitHub Issue / Comment** 視為原始事實來源，任何摘要或結論皆須基於這些資料。  
  - **Shared Manual Notes**（`shared/manual.md`）是人工維護的長期記憶，裡面的內容屬於穩定規則、決策與限制，**不會被自動流程覆寫**。  
  - 任何自動化的記憶蒸餾（如 daily snapshots）**不得直接複製**原始 Issue 文字，必須以精煉、可重用的形式呈現。  

- **Repo 習慣**  
  - 每日快照（`daily/*.json`）會在過去 30 天內搜尋可用 Issue，若無則保留既有記憶。  
  - 跨 Issue 的主題、決策與未完成事項（Open Loops）會在有新 Issue 時重新評估。  
  - **Top Labels** 會被用來快速辨識當前關注的領域，若無標籤則視為無明顯焦點。  

- **長期決策**  
  - 目前尚未有跨 Issue 的正式決策記錄。  

## Recent Themes
- **無可辨識的跨 Issue 主題**  
  - 從 2026‑07‑27 至 2026‑08‑02 的每日快照皆顯示「目前沒有可辨識的跨 issue 主題」。  
- **持續缺乏可用 Issue**  
  - 每日快照皆報告「本次整理視窗沒有可用 issue」，表示近期（至少過去兩週）專案內缺乏活躍的 Issue。  

> **備註**：若未來出現新 Issue，相關主題將在此區塊更新。

## Constraints
1. **資料來源限制**  
   - 只能引用 Issue / Comment 作為事實依據；手動筆記僅供參考與規則。  
2. **避免冗餘**  
   - 不得逐段複製原始 Issue 文字，必須以「可重用」的摘要形式保存。  
3. **更新頻率**  
   - 只在有新 Issue 時才重新整理 Open Loops、Cross‑Issue Themes 與 Decisions。  
4. **手動筆記保護**  
   - `shared/manual.md` 由人類維護，系統不會自動覆寫或刪除其中內容。  

## Open Loops
- **等待 Issue 更新**  
  - 目前所有每日快照的「Open Loops」皆為「等待下一輪 issue 更新後再整理」。  
  - 這表示目前沒有待處理的任務
