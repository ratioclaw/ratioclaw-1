# Repository Memory

## Stable Context
- 目前 **沒有** 從 issue 中萃取出的長期穩定規則或決策。  
- 依照 **Shared Manual Notes**，以下原則仍然適用於整個 repo：  
  - 所有事實與決策的原始來源必須是 **GitHub Issue / Comment**，手動筆記僅作為摘要與輔助說明。  
  - `compact‑memory` 工作流程會 **讀取** 這份手動筆記，但 **不會覆寫**，因此手動筆記的內容應保持不變，僅供參考。  
- 由於過去 30 天的 daily snapshots 均未偵測到可用 issue，故無法確認任何持續性的工作流程、命名慣例或技術選型。  

> **不確定性**：若未來出現新的 issue，可能會產生新的穩定規則，需在下一次記憶更新時補充。

---

## Recent Themes
- **無跨 issue 主題**：連續七天（2026‑09‑03 至 2026‑09‑09）的快照皆報告「目前沒有可辨識的跨 issue 主題」。
- **無新決策**：同樣期間內未出現任何跨 issue 的決策紀錄。  
- **無活躍 issue**：每日的「Agent Activity」皆顯示「本次整理視窗沒有可用 issue」，表示近期 repo 內缺乏待處理或新建立的議題。

---

## Constraints
1. **資料來源限制**  
   - 只能以 GitHub Issue / Comment 為事實與決策的根據，任何手動筆記皆屬次要資訊。  
2. **手動筆記的角色**  
   - `shared/manual.md` 為 **長期記憶的手動維護區**，不應被自動流程覆寫。  
3. **記憶更新頻率**  
   - 目前的 daily snapshot 只在有可用 issue 時才會產生實質內容，若無 issue，系統會保留既有記憶並等待下一輪更新。  

---

## Open Loops
- **等待 Issue 更新**：所有 daily snapshots 均顯示「等待下一輪 issue 更新後再整理」，因此目前沒有任何待完成的具體任務。  
- **未來可能的主題**：若未來出現新 issue，需重新評估是否形成跨 issue 主題、決策或新穩定規則。  

--- 

> **龍蝦的提醒**：目前的記憶庫相當空白，請確保在日常開發中適時建立與更新
