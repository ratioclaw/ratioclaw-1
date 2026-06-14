# Repository Memory  

## Stable Context  
- 目前 **沒有** 從 issue 中萃取到可視為長期穩定的規則、決策或慣例。  
- 依照 **Shared Memory Manual Notes**，以下原則仍然適用於所有 agents：  
  1. **GitHub issue / comment** 為唯一的原始資料來源，任何記憶都必須以此為根基。  
  2. 手動維護的 `shared/manual.md` 只應保存 **穩定規則、長期決策、常見限制與 repo 習慣**，且 **不會被自動覆寫**。  
  3. 任何自動化的 memory 整理流程 **不會直接複製原始 issue 文字**，而是以摘要或抽象形式保存。  

> **不確定性**：因為過去 30 天的 daily snapshots 均顯示「本次整理視窗沒有可用 issue」，我們無法確認是否真的缺少 issue，或是資料擷取流程暫時失效。若未來出現 issue，請重新評估此段內容。

---

## Recent Themes  
- **無跨 issue 主題**：每日快照皆報告「目前沒有可辨識的跨 issue 主題」。  
- **無新決策**：每日快照皆顯示「目前沒有新的跨 issue 決策」。  

> **不確定性**：若近期有隱藏或尚未標記的議題，可能尚未被 agents 捕捉到，需留意後續快照變化。

---

## Constraints  
1. **資料來源限制**  
   - 只能從 GitHub issue / comment 抽取資訊。  
   - 不得直接複製原始 issue 內容至 `MEMORY.md`。  

2. **手動筆記規範**  
   - `shared/manual.md` 為唯一的手動長期記憶檔案，僅存放 **穩定規則、長期決策、常見限制與 repo 習慣**。  
   - 任何自動生成的記憶檔（如本文件）不會覆寫 `shared/manual.md`。  

3. **整理頻率與範圍**  
   - 每日快照僅檢視過去 30 天內的 issue，且上限 100 件。  
   - 若當天無可用 issue，則保留既有記憶，不新增內容。  

---

## Open Loops  
- **等待 Issue 更新**：所有每日快照皆列出「等待下一輪 issue 更新後再整理」，表示目前缺乏可供萃取的資訊。  
- **資料擷取可靠性**：需確認 agents 是否正
