# Repository Memory

## Stable Context
- **長期規則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何記憶內容皆須根據這些來源抽象、濃縮。  
  - `shared/manual.md` 為人工維護的長期記憶檔案，**不會**被自動流程覆寫，僅供參考與補充。  
  - 任何自動產出的記憶（如 daily snapshots）必須避免直接複製原始 Issue 文字，必須以「概念」或「規則」的形式呈現。  

- **長期決策**  
  - 目前尚未有跨 Issue 的決策被記錄，故無固定決策可列入。  

- **常見限制**  
  - 每日快照只會在 **過去 30 天內**、**狀態為 all**、且 **上限 100** 的 Issue 中搜尋。若期間內無可用 Issue，快照將僅保留既有記憶。  
  - 任何新資訊若僅在單一天出現且未形成穩定事實，必須歸入「近期主題」或「未完成事項」而非寫成永久規則。  

- **Repo 習慣**  
  - 使用 **compact‑memory workflow**：  
    1. 讀取 `shared/manual.md` 取得穩定規則與限制。  
    2. 解析每日快照，抽取跨 Issue 主題與決策。  
    3. 只在 `MEMORY.md` 中寫入 **精煉後的長期可重用上下文**。  
  - 每日快照的結構固定為：Agent Activity、Cross‑Issue Themes、Decisions、Open Loops、Top Labels。  

## Recent Themes
- **缺乏可用 Issue**  
  - 2026‑05‑10 至 2026‑05‑16 的每日快照皆顯示「本次整理視窗沒有可用 issue」，說明近期（過去一週）專案內沒有新開或待處理的 Issue。  
- **無跨 Issue 主題**  
  - 所有快照均報告「目前沒有可辨識的跨 issue 主題」，表示目前沒有多 Issue 之間的共通議題需要統整。  

> **註**：上述主題僅反映最近一週的觀測，若未來出現 Issue，主題將隨之更新。

## Constraints
1. **資料來源限制**  
   - 只能從 GitHub Issue / Comment 抽取資訊，其他來源（如聊天記錄、外部文件）不列入記憶範圍。  
2. **內容精簡原則**  
   - 不得直接搬錄
