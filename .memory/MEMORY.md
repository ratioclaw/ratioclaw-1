# Repository Memory

## Stable Context
- **目前尚未從 issue 中萃取到任何穩定規則或長期決策。**  
  由於過去 30 天的 daily snapshots 均顯示「本次整理視窗沒有可用 issue」，我們無法辨識出持續性的工作流程、程式碼風格或其他長期遵循的原則。  
- **手動維護的 Shared Memory Manual**（`shared/manual.md`）被視為唯一的長期記錄來源，內容應包括：  
  - 穩定規則  
  - 長期決策  
  - 常見限制  
  - repo 內部的協作慣例  
  目前此檔案僅說明了「不應完整複製 issue 原文」以及「compact‑memory workflow 只會讀取不會覆寫」等 meta‑資訊，未提供具體規則。  
- **不確定性**：因缺乏具體資料，我們無法斷言任何「穩定」的上下文。未來若有可用的 issue，請務必將其核心規則或決策寫入 `shared/manual.md` 以形成真正的長期記憶。

## Recent Themes
- **無可辨識的跨 issue 主題**：2026‑07‑01 至 2026‑07‑07 的所有 daily snapshots 均報告「目前沒有可辨識的跨 issue 主題」。
- **暫無重複出現的議題**：每日皆未檢測到任何活躍 issue，故無法抽取近期重點或趨勢。

## Constraints
1. **資料來源限制**  
   - 只能從 GitHub Issue / Comment 中抽取原始資訊，`shared/manual.md` 僅作為摘要與規則的存放地。  
2. **內容寫入規則**  
   - `shared/manual.md` 不應被自動覆寫；它僅供 `compact-memory workflow` 讀取。  
   - 任何新發現的穩定規則或決策必須由人類手動加入此檔案。  
3. **記錄範圍**  
   - Daily snapshots 只會列出過去 30 天內的 issue；若超出此範圍或 issue 被關閉，將不會出現在快照中。  
4. **語氣與風格**  
   - 本記憶檔案以「龍蝦」的視角撰寫，需保持工程
