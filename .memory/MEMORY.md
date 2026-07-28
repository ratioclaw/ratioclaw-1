# Repository Memory

## Stable Context
- 目前在 **ratioclaw/ratioclaw-1** 的 issue 系統中，過去 30 天內未出現任何可用的 issue。  
- 依照 **Shared Memory Manual Notes**，以下規則被視為長期穩定且必須遵守：
  1. **資料來源**：所有原始資訊必須來自 GitHub issue 或 comment，手動筆記僅作為摘要與輔助說明。  
  2. **手動筆記的角色**：`shared/manual.md` 供人類維護長期記憶，**不會被自動覆寫**，且不應直接複製完整的 issue 內容。  
  3. **compact‑memory 工作流程**：會讀取 `shared/manual.md` 作為上下文，但不會改寫此檔案。  
  4. **repo 習慣**：所有 agents 必須共同遵守上述規範，確保記憶的完整性與可追溯性。

> **不確定性**：除上述手動筆記的規則外，因缺乏任何活躍 issue，無法辨識其他長期穩定的業務規則或決策。

## Recent Themes
- 最近七天（2026‑07‑22 至 2026‑07‑28）內，**未偵測到任何跨 issue 主題**、決策或標籤。  
- 系統持續回報「本次整理視窗沒有可用 issue，先保留既有記憶」。

## Constraints
1. **資訊來源限制**  
   - 只能使用 GitHub issue / comment 作為原始資料。  
   - 手動筆記僅作為摘要，不能取代原始 issue。

2. **內容複製限制**  
   - 不得完整複製 issue 原文於 `shared/manual.md` 或其他長期記憶檔案。

3. **更新頻率**  
   - 若無新 issue，agents 必須保留現有記憶，並在下一輪 issue 更新時重新整理。

4. **可讀性要求**  
   - 長期記憶必須保持工程可讀性，使用 Markdown 結構化呈現。

## Open Loops
- **待處理的 Issue**：目前無可用 issue，所有未完成事項皆待下一輪 issue 更新後再行整理。  
- **未確定的長期規則**：因缺乏實際案例，尚未能確認除手動筆記中列出的規則外，是否存在其他
