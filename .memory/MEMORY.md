# Repository Memory

## Stable Context
- 目前 **shared/manual.md** 中僅列出應保存的類型（穩定規則、長期決策、常見限制、repo 習慣），但未提供具體內容。  
- 由於過去 30 天的 daily snapshots 均未檢測到任何可用 Issue，系統無法自動抽取或驗證任何穩定規則或長期決策。  
- **不確定性**：缺乏實際的 Issue 資料，使得此區塊仍需人工補充，以確保長期記憶的完整性。

## Recent Themes
- 最近 30 天（2026‑07‑31 至 2026‑08‑07）所有 daily snapshot 均報告「本次整理視窗沒有可用 issue」，因此未出現可辨識的跨 Issue 主題或重複出現的議題。  
- **結論**：目前無近期主題可供蒸餾。

## Constraints
- **Issue 依賴**：記憶抽取流程依賴 GitHub Issue / comment 作為原始資料來源。若 Issue 不活躍或未建立，記憶將無法自動更新。  
- **手動筆記限制**：shared/manual.md 只能作為輔助，系統不會覆寫其中內容；若手動筆記缺失，系統亦無法自行補全。  
- **資料時效**：每日快照僅檢視最近 30 天內的 Issue，超出此範圍的歷史資訊不會自動納入本記憶檔。

## Open Loops
- **等待 Issue 更新**：所有快照皆顯示「等待下一輪 issue 更新後再整理」，表示目前缺少待處理的 Issue。  
- **缺失的穩定規則與決策**：需要人工在 `shared/manual.md` 中填入具體的穩定規則、長期決策、常見限制與 repo 習慣，以便未來的記憶蒸餾。  
- **未來主題偵測**：若未來出現持續出現的 Issue 主題，需將其歸類至「Recent Themes」或升級為「Stable Context」的規則。  

---  
*此文件由一群勤奮的龍蝦整理，旨在為主人保留長期可重用的 repository 記憶。若有任何新 Issue 或手動筆記更新，請即時通知我們，以
