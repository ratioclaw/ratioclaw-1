# Repository Memory

## Stable Context
- **長期規則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何手動筆記皆為輔助說明，**不會**直接覆寫原始 Issue。  
  - `compact‑memory` 工作流程會讀取 **shared/manual.md**，但不會改寫它；因此此檔案的內容必須保持 **穩定且可重用**。  
  - 所有自動化 agents 必須遵守 repo 的共通慣例：  
    1. 先檢查 Issue 是否可用，若無則保留既有記憶。  
    2. 只在跨 Issue 有明顯關聯時才產生 **Cross‑Issue Themes** 或 **Decisions**。  
    3. 未完成的事項以 **Open Loops** 形式列出，待後續 Issue 更新時再處理。  

- **長期決策**  
  - 目前尚未有跨 Issue 的決策產生，表示專案在近期內保持穩定、無重大變更。  

- **常見限制**  
  - 不得直接複製 Issue 原文於手動筆記或長期記憶檔。  
  - 只能蒸餾出「規則」與「可重用的上下文」，避免冗長的日誌堆砌。  
  - 若資訊不足或相互矛盾，必須在 **Open Loops** 中標註「不確定性」供後續確認。  

## Recent Themes
- **無可辨識的跨 Issue 主題**  
  - 從 2026‑11‑19 至 2026‑11‑26 的每日快照皆顯示「本次整理視窗沒有可用 issue」，因此近期未出現重複或新興的主題。  

## Constraints
1. **資料來源限制**  
   - 只能從 `.memory/daily/*.json` 以及 `shared/manual.md` 取得資訊。  
2. **編寫規範**  
   - 本文件 **不是** 原始日誌，也 **不是** 索引頁；它必須是 **curated long‑term memory**，以工程可讀性為主。  
3. **更新頻率**  
   - 若未偵測到可用 Issue，agents 必須保留現有記憶，並在下一輪 Issue 更新時重新評估。  
4. **不確定資訊處理**  
   - 任何僅在單一天出現且未形成穩定事實的資訊，必須放入 **Open Loops**，不應寫成永久規則。  

## Open Loops
- **等待 Issue 更新**  
  - 2026‑11‑19 至 2026‑11‑26
