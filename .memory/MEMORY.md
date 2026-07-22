# Repository Memory

## Stable Context
- **記憶流程**：本倉庫採用 *compact‑memory* 工作流，所有 agents 皆以 `shared/manual.md` 為長期記憶的根基，日常快照只負責從當天活躍的 Issue 中抽取可重用的資訊。  
- **穩定規則**  
  1. **不直接複製 Issue 原文**：只能以摘要或抽象概念保存，避免冗長與重複。  
  2. **手動筆記不會被覆寫**：`shared/manual.md` 只由人類維護，系統僅讀取不寫入。  
  3. **每日快照只在有可用 Issue 時才產出主題、決策與跨 Issue 主題**。  
- **Repo 習慣**  
  - Issue / comment 為唯一的原始資料來源。  
  - 每日快照 (`daily/*.json`) 會在 30 天內的 Issue 中搜尋，若無則保留既有記憶。  
  - 產出內容必須符合四大章節：`Stable Context`、`Recent Themes`、`Constraints`、`Open Loops`。  

## Recent Themes
- **2026‑07‑16 ~ 2026‑07‑22**：連續七天的快照皆顯示「本次整理視窗沒有可用 issue」，因此未偵測到任何跨 Issue 主題、決策或新興趨勢。  
- **無新主題**：目前沒有重複出現的議題或概念可蒸餾為長期可重用的上下文。  

## Constraints
- 必須以繁體
