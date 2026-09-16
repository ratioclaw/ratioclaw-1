# Repository Memory  

## Stable Context  
- **長期規則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何記憶內容皆須根據這些來源抽象、濃縮。  
  - `shared/manual.md` 為唯一人工維護的長期記憶檔案，**不會**被自動流程覆寫。  
  - 任何自動產出的摘要（如 daily snapshots）只能**蒸餾**出可重用的規則或決策，絕不能直接複製原始 Issue 文字。  

- **長期決策**  
  - 目前尚未在 Issue 中形成跨議題的決策，故無可記錄的長期決策。  

- **常見限制**  
  - 只能在 `daily/` 目錄內的 JSON 快照中取得最近 30 天內的 Issue 資訊。  
  - 若快照顯示「本次整理視窗沒有可用 issue」，則代表當前沒有可供蒸餾的資料。  
  - 任何新資訊必須在下一輪 Issue 更新後才會被納入記憶。  

- **repo 習慣**  
  - 使用 **compact‑memory workflow**：  
    1. 讀取 `shared/manual.md` 取得穩定規則。  
    2. 解析最近的 daily snapshots，抽取跨 Issue 主題與決策。  
    3. 只在 `MEMORY.md` 中寫入 **長期可重用** 的上下文，避免冗餘。  
  - `MEMORY.md` 只保留 **策展後的長期記憶**，不作為日誌或索引頁。  

## Recent Themes  
- 2026‑09‑10 至 2026‑09‑16 的所有 daily snapshots 均顯示 **「本次整理視窗沒有可用 issue」**，因此目前沒有可辨識的跨 Issue 主題或近期重複出現的議題。  

## Constraints  
1. **資料來源限制**：只能引用 GitHub Issue / Comment，不能直接貼上原始 Issue 內容。  
2. **更新頻率**：記憶的更新依賴於 Issue 的產生與變更；若無新 Issue，記憶保持不變。  
3. **手動筆記保護**：`shared/manual.md` 由人類維護，系統不會覆寫或自動修改此檔。  
4. **格式要求**：`MEMORY.md` 必須以 Markdown 撰寫，首行為 `# Repository Memory`，並包含四個固定子節。  

## Open Loops  
- **等待 Issue 更新**：目前所有 daily snapshots 均未捕捉到可用
