# Repository Memory

## Stable Context
- **手動筆記檔案**：`shared/manual.md` 被指定為 **長期記憶的唯一手動維護入口**，用來保存  
  - 穩定規則  
  - 長期決策  
  - 常見限制  
  - Repo 內部慣例  
  此檔案 **不會被 agents 覆寫**，且僅供 `compact-memory` 工作流讀取。  
- **資料來源原則**：所有可供記憶的事實必須來自 **GitHub Issue / Comment**，手動筆記僅作為摘要與指引，不能直接複製原始 Issue 內容。  
- **目前無可用 Issue**：過去 30 天的每日快照皆顯示「本次整理視窗沒有可用 issue」，因此 **尚未形成任何可供抽象化的穩定規則或決策**。

## Recent Themes
- **無跨 Issue 主題**：每日快照的 *Cross‑Issue Themes* 欄位皆為「目前沒有可辨識的跨 issue 主題」。
- **無新決策**：*Decisions* 欄位皆為空，表示近期沒有跨 Issue 的共識或變更。
- **等待更新**：所有快照的 *Open Loops* 均寫明「等待下一輪 issue 更新後再整理」，顯示目前的主要活動是 **待命**，等待新 Issue 的出現。

## Constraints
1. **來源限制**  
   - 只能以 Issue / Comment 為事實來源；手動筆記僅作為輔助說明。  
2. **寫入限制**  
   - `shared/manual.md` 只能被人類手動編輯，agents 不得直接寫入或覆寫。  
3. **記憶流程**  
   - `compact-memory` 只會 **讀取** 手動筆記，不會改寫；因此任何新穩定規則必須先透過 Issue 討論形成，才會被手動匯入。  
4. **缺乏資訊**  
   - 目前缺少任何可驗證的 Issue 內容，導致 **無法確定**
