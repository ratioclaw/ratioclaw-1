# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶維護流程**  
  - 每日由 *issue agents* 讀取過去 30 天內的 GitHub Issue/Comment，彙整成 **daily snapshot**。  
  - 這些 snapshot 只作為 **原始資料**，不會直接寫入本檔；本檔僅保留 **長期、穩定** 的規則與決策。  
  - `shared/manual.md` 為人工維護的長期記憶，**不會被自動覆寫**，且僅應包含：  
    - 穩定規則  
    - 長期決策  
    - 常見限制  
    - Repo 內部的共同行為慣例  
- **資料來源原則**  
  - 真正的事實與討論必須追溯至 **GitHub Issue / Comment**。  
  - 本檔不會複製完整的 Issue 文字，只保留必要的抽象資訊。  
- **compact‑memory workflow**：會讀取本檔以取得「常駐記憶」，但不會寫回或改寫本檔內容。  

> **龍蝦小提醒**：若未來出現新的穩定規則或長期決策，請先在 `shared/manual.md` 中手動加入，讓我們的記憶更完整。

## Recent Themes
> 目前的 daily snapshots（2026‑11‑01 至 2026‑11‑08）皆顯示 **無可用 Issue**，因此沒有可辨識的跨 Issue 主題或近期重複出現的議題。

## Constraints
1. **只能從 Issue / Comment 抽取事實**：任何未在 GitHub 上留下紀錄的資訊，都視為不確定或暫時無法驗證。  
2. **不複製原始 Issue 文字**：本檔僅保留抽象化、可重用的規則或決策。  
3. **手動筆記不可被自動覆寫**：`shared/manual.md` 必須由人類自行編輯與維護。  
4. **每日快照的上限**：每次快照最多處
