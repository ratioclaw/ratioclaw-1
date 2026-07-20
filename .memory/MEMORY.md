# Repository Memory

## Stable Context
- **記憶維護原則**  
  - 只保留 **穩定規則、長期決策、常見限制** 以及 **repo 共同習慣**，不直接複製 Issue 原文。  
  - 所有原始資訊皆來自 GitHub Issue / Comment，這些才是事實的唯一來源。  
  - `compact‑memory` 工作流程會讀取本檔案，但不會覆寫它。  

- **目前可確認的長期事實**  
  - 目前 **沒有可用的 Issue**（過去 30 天內皆無），因此沒有新增的穩定規則或決策可加入。  
  - 共享手動筆記 (`shared/manual.md`) 已被確認為 **唯一的長期記憶來源**，其內容即為目前的穩定上下文。  

> **不確定性**：因缺乏 Issue 資料，無法判斷主人在工作、生活或專案上的其他長期規則或偏好。

## Recent Themes
- **無跨 Issue 主題**：連續 7 天的 daily snapshot 均未偵測到任何跨 Issue 的共通主題。  
- **無新決策**：同樣沒有新出現的跨 Issue 決策。  

> **觀察**：近期（過去一週）系統未收到任何可供分析的 Issue，故無法抽取近期重複出現的主題。

## Constraints
1. **資料來源限制**  
   - 只能引用 GitHub Issue / Comment 作為事實依據。  
   - 不得直接複製完整 Issue 文字於本檔案。  

2. **記憶更新規則**  
   - `compact‑memory` 只會 **讀取** 本手動筆記，不會 **覆寫**。  
   - 若每日快照未偵測到可用 Issue，則保留既有記憶，不新增或刪除內容。  

3. **內容結構要求**  
   - 本檔案必須以 Markdown 撰寫，包含四大節：`Stable Context`、`Recent Themes`、`Constraints`、`Open Loops`。  
   - 語氣需保持「龍蝦」的口吻，兼具工程可讀性。  

## Open Loops
- **等待 Issue 更新**：目前所有每日快照皆顯示「等待下一輪 issue 更新後再整理」，因此以下項目仍未解決：  
  - 是否有即將產生的 Issue 需要納入長期記憶？  
  - 是否有尚未被捕
