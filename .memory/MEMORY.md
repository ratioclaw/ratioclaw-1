# Repository Memory

## Stable Context
- 目前在過去 30 天的 daily snapshots 中，未偵測到任何可視為 **長期穩定規則**、**長期決策** 或 **常見限制**。  
- 依據 `shared/manual.md` 的說明，穩定規則與長期決策應由人類手動維護於此檔案，但目前尚未有具體條目可供蒸餾。  
- 若未來出現持續出現在多個 issue 或日誌中的行為模式，請將其加入此節作為穩定上下文。

## Recent Themes
- 最近 30 天（2026‑10‑31 至 2026‑11‑07）所有 daily snapshots 均顯示 **「本次整理視窗沒有可用 issue」**，因此沒有跨 issue 的主題或重複出現的討論。  
- 暫無可歸納的近期主題。

## Constraints
1. **資料來源限制**  
   - 只有 GitHub Issue / Comment 被視為原始、可信的事實來源。  
   - 任何自動化流程（如 compact‑memory workflow）不得直接覆寫 `shared/manual.md` 中的手動筆記。

2. **流程約束**  
   - 當前的 daily snapshot 只在有可用 issue 時才會產生跨 issue 主題、決策或 open loops。  
   - 若無 issue，系統會保留既有記憶並等待下一輪更新。

3. **可讀性與工程化**  
   - 所有記憶條目須保持 Markdown 可讀、結構化，方便 agents 解析與引用。  

## Open Loops
- **等待 Issue 更新**：目前所有 snapshot 均顯示「等待下一輪 issue 更新後再整理」，因此沒有具體的未完成事項。  
- **資訊不足**：因缺乏 issue 資料，無法確定任何潛在
