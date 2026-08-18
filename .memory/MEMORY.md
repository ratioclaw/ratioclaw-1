# Repository Memory

## Stable Context
- **長期規則**  
  - 只將 **GitHub Issue / Comment** 視為原始事實來源，任何摘要或結論皆須基於這些資料。  
  - `shared/manual.md` 為 **手動維護的長期記憶**，不會被自動流程覆寫，亦不應直接複製完整 Issue 內容。  
  - 任何自動化的 **compact‑memory workflow** 必須先讀取 `shared/manual.md`，再將新資訊以 **濃縮、去重** 的方式加入本檔案。  

- **Repo 習慣**  
  - 每日快照 (`daily/*.json`) 由活躍的 issue agents 產出，若當天無可用 Issue，則保留既有記憶不做變更。  
  - 跨 Issue 的主題、決策與未完成事項（Open Loops）皆應在每日快照中顯示，若缺失則視為「暫無可辨識」。  

- **資訊層級**  
  1. **Stable Context**：長期不變、所有成員皆遵守的規則與決策。  
  2. **Recent Themes**：過去 30 天內多次出現的主題或趨勢。  
  3. **Constraints**：對行為、資料處理、寫作風格的限制。  
  4. **Open Loops**：尚未解決、需要後續 Issue 更新的事項。  

## Recent Themes
- **無可辨識的跨 Issue 主題**  
  - 2026‑08‑12 至 2026‑08‑18 的每日快照皆顯示「目前沒有可辨識的跨 issue 主題」。  
- **持續缺乏可用 Issue**  
  - 連續七天（2026‑08‑12~2026‑08‑18）皆未檢測到可用 Issue，說明目前 repo 內的工作項目可能處於靜止或已全部關閉狀態。  

> **註**：若未來出現新 Issue，相關主題將自動移入此區塊。

## Constraints
1. **資料來源限制**  
   - 只能引用 Issue / Comment，不能直接搬錄原始文字至本檔。  
2. **手動筆記保護**  
   - `shared/manual.md` 為唯一的手動長期記憶檔案，任何自動化流程不得覆寫或刪除其內容。  
3. **摘要原則**  
   - 必須將每日快照的重複資訊「蒸餾」成可重用的長期上下文，避免逐段複製。  
4. **不確定資訊
