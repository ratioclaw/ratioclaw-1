# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶維護流程**  
  - 所有長期記憶皆以 **shared/manual.md** 為唯一手動維護來源。  
  - 任何自動產生的 daily snapshot 只作為 **暫存**，不會直接寫入此檔。  
  - 只有 **GitHub Issue / Comment** 被視為原始事實來源，其他摘要僅供參考。  
- **repo 習慣**（根據手動筆記）  
  1. **不**將完整 Issue 內容複製到長期記憶檔。  
  2. **compact‑memory workflow** 會讀取本檔，但不會覆寫本檔。  
  3. 穩定規則、長期決策、常見限制應寫在此手動筆記中，供所有 agents 共享。  

> **註**：目前未在手動筆記中發現其他具體的穩定規則或長期決策。

## Recent Themes
- **無可辨識的跨 Issue 主題**（2026‑08‑29 至 2026‑09‑04 的所有 daily snapshots 均未檢測到）。  
- **每日快照** 皆顯示「本次整理視窗沒有可用 issue」，表示近期 **issue 活動為零**。  

## Constraints
1. **資訊來源限制**  
   - 只能依賴 `shared/manual.md` 中的手動條目與 **GitHub Issue / Comment**。  
   - Daily snapshot 只作為暫時觀測，不能直接成為長期規則。  
2. **內容呈現限制**  
   - 本檔案 **不**是原始日誌或索引頁，必須是 **curated**（精煉）版的長期記憶。  
   - 不得逐段複製原始 Issue 文字。  
3. **不確定性處理**  
   - 若資訊不足或相互矛盾，必須在相應節點標註「不確定」或「缺乏資料」。  

## Open Loops
- **等待 Issue 更新**：所有 daily snapshots（2026‑08‑29 ~ 2026‑09‑04）皆顯示「等待下一輪 issue 更新後再整理」。目前沒有任何待處理的 issue。  
- **缺乏新資訊**：因近期無可用 issue，尚未產生新的跨
