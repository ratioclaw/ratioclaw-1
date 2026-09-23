# Repository Memory

## Stable Context
- 目前的每日快照（2026‑09‑17 至 2026‑09‑23）皆未偵測到可用的 Issue，故無法抽取任何長期穩定規則或決策。  
- **資料來源原則**：所有 agent 必須以 GitHub Issue / Comment 為唯一真實資料來源，任何手動筆記僅作為輔助、不可直接取代原始 Issue 內容。  
- **手動筆記 (`shared/manual.md`)**：用於人類維護的長期記憶，僅收錄穩定規則、長期決策、常見限制與 repo 習慣；agents 讀取但不會覆寫此檔。  
- **compact‑memory 工作流程**：會讀取 `shared/manual.md`，但不會自動寫入或覆寫，確保手動維護的內容保持完整。

## Recent Themes
- 最近一週的快照皆顯示「本次整理視窗沒有可用 issue」，因此未出現任何跨 Issue 主題或重複出現的討論。  
- 沒有可辨識的近期關注點或新興議題。

## Constraints
1. **Issue 為唯一真實來源**  
   - 所有決策、規則與限制必須以 Issue / Comment 為根據，手動筆記僅作為摘要與補充。  
2. **手動筆記的使用規範**  
   - 不得直接複製完整 Issue 文字至 `shared/manual.md`。
