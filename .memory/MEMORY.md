# Repository Memory

## Stable Context
- **記憶管理原則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何長期記憶皆須根據這些來源抽象、濃縮。  
  - `shared/manual.md` 為人類手動維護的長期記憶檔案，裡面放置 **穩定規則、長期決策、常見限制、repo 習慣**，系統不會自行覆寫此檔。  
  - `compact‑memory` 工作流程會在每次執行時讀取 `shared/manual.md`，但不會把原始 Issue 內容完整複製進去，只保留精煉後的概念。  
- **Agent 行為**  
  - 當前的每日快照顯示 **無可用 Issue**，因此所有 Agent 皆保持「待命」狀態，僅保留既有記憶。  
  - 若未來出現 Issue，Agent 會根據 Issue 標籤、標題與內容抽取跨 Issue 主題、決策與未完成事項，並更新本檔。  
- **Repo 習慣**  
  - 每日產出 `daily/YYYY-MM-DD.json`，內容包括：Agent Activity、Cross‑Issue Themes、Decisions、Open Loops、Top Labels。  
  - 只保留最近 30 天、最多 100 個 Issue 的摘要，以避免記憶膨脹。  

## Recent Themes
> 近期（過去 30 天）未偵測到任何跨 Issue 主題或重複出現的議題。所有快照皆報告「本次整理視窗沒有可用 issue」，因此目前沒有可供蒸餾的主題。

## Constraints
1. **不複製原始 Issue 文字**：任何長期記憶必須以概念或規則形式呈現，避免直接貼上 Issue 內容。  
2. **手動筆記優先**：`shared/manual.md` 中的條目視為最高優先級，系統只能在其基礎上增補，不能覆寫。  
3. **資料範圍限制**：每日快照僅考慮最近 30 天、最多 100 個 Issue；超出範圍的資訊將不會自動納入長期記憶。  
4. **等待 Issue 更新**：在沒有可用 Issue 時
