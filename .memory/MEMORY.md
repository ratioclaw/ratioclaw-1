# Repository Memory

## Stable Context
- **長期規則**  
  - 只以 GitHub Issue 或 Comment 為原始資料來源，任何記憶內容皆須可追溯至這些來源。  
  - `shared/manual.md` 為人工維護的長期記憶檔案，**不會**被自動流程覆寫。  
  - 任何自動化流程（如 compact‑memory）只能**讀取**此手動筆記，不能寫入或改寫。  

- **共通決策**  
  - 目前尚未有跨 Issue 的新決策；所有既有決策皆已在手動筆記中記錄。  

- **Repo 習慣**  
  - 每日快照 (daily snapshots) 會在過去 30 天內檢索最多 100 個 Issue，若無可用 Issue，則保留既有記憶不變。  
  - 快照結果會被歸類為「Agent Activity」「Cross‑Issue Themes」「Decisions」「Open Loops」四大區塊，供龍蝦們後續蒸餾。  

## Recent Themes
- **缺乏可用 Issue**  
  - 2026‑06‑19 至 2026‑06‑25 的連續七天快照皆顯示「本次整理視窗沒有可用 issue」，說明近期 repo 內的 Issue 活動極低或已全部關閉。  
- **無跨 Issue 主題**  
  - 每日快照皆未偵測到可辨識的跨 Issue 主題，表示目前沒有正在進行的多 Issue 交叉討論。  

> **備註**：上述主題僅基於最近七天的快照，若未來出現新 Issue，主題可能會隨之變化。

## Constraints
1. **資料來源限制**  
   - 只能引用 GitHub Issue / Comment，其他非結構化來源（如聊天記錄、部落格）不列入正式記憶。  
2. **內容重複限制**  
   - 不得直接複製 Issue 原文或完整段落，必須以摘要或抽象化方式呈現。  
3. **手動筆記保護**  
   - `shared/manual.md` 為唯一手動維護的長期記憶檔，任何自動化流程不得修改此檔。  
4. **快照範圍**  
   - 每次快照僅檢索最近 30 天內、狀態為任意、上限 100 個 Issue。超出此範圍的資訊不會自動納入記憶。  

## Open Loops
- **等待新 Issue**
