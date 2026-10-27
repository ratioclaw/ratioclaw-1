# Repository Memory

## Stable Context
- **資料來源原則**  
  - 只有 GitHub Issue 與 Comment 被視為原始事實來源。  
  - 任何手動筆記（如本檔）僅作為 **摘要與規則**，不會直接覆寫原始 Issue 內容。  

- **手動筆記的角色**  
  - `shared/manual.md` 用於保存 **長期穩定規則、決策、常見限制與 repo 習慣**。  
  - 這份筆記不會被自動流程（compact‑memory workflow）改寫，僅供 agents 參考。  

- **repo 習慣（目前已知）**  
  - 以每日快照（`daily/*.json`）彙整當前活躍 Issue。  
  - 若快照期間無可用 Issue，則保留既有記憶，不產生新條目。  

- **已確認的穩定事實**  
  - 近期 10 天（2026‑10‑21 至 2026‑10‑27）內，**所有快照皆未偵測到可用 Issue**。  
  - 因此目前 **沒有跨 Issue 主題、決策或待辦事項**。  

## Recent Themes
> 目前的快照未顯示任何可辨識的跨 Issue 主題或重複出現的討論。  
> 若未來出現新 Issue，相關主題將在此區塊更新。

## Constraints
1. **原始資料限制**  
   - 只能從 GitHub Issue / Comment 抽取事實；手動筆記僅作為輔助說明。  
2. **內容重複規則**  
   - 不得在本檔直接複製 Issue 原文；需以摘要或規則形式呈現。  
3. **自動流程行為**  
   - `compact-memory workflow` 會讀取本手動筆記，但不會覆寫或刪除其中內容。  
4. **資訊不確定性**  
   - 目前缺乏任何 Issue 資料，故無法確定任何新規則、決策或限制。  

## Open Loops
- **等待 Issue 更新**  
  - 目前所有每日快照皆顯示「等待下一輪 Issue 更新後再整理
