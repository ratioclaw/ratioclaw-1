# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶維護流程**  
  - 每日由 issue agents 產出 snapshot，彙整當前 issue 狀態。  
  - `shared/manual.md` 為人工維護的長期記憶檔，僅存放 **穩定規則、長期決策、常見限制、repo 習慣**，不會被自動覆寫。  
  - `compact‑memory workflow` 只會讀取此手動筆記，不會寫入或刪除內容。  
- **目前觀測**  
  - 連續 7 天（2026‑08‑26 至 2026‑09‑02）皆未偵測到可用 issue，表示近期 repo 內無活躍工作項目。  
  - 因無跨‑issue 主題或決策，長期記憶仍維持在手動筆記的基礎上。

## Recent Themes
> 近期（過去 30 天）未出現可辨識的跨 issue 主題或重複出現的討論點。  
> 若未來出現新議題，將在此區塊加入相應主題摘要。

## Constraints
1. **內容來源限制**  
   - 只能引用 GitHub Issue / Comment 作為原始資料來源。  
   - 不得直接複製完整 Issue 文字至 `MEMORY.md`，必須以摘要或抽象方式呈現。  
2. **手動筆記保護**  
   - `shared/manual.md` 為唯一手動編輯的長期記憶檔，系統不會自動覆寫。  
   - 任何自動生成的記憶（如本文件）必須避免與手動筆記內容衝突。  
3. **記憶蒸餾原則**  
   - 只保留 **穩定規則**、**長期決策**、**常見限制**、**repo 習慣**。  
   - 短暫、未確定的資訊應放入「Open Loops」或「Recent Themes」區塊。  
4. **語言與風格**  
   - 以繁體中文撰寫，語氣模擬「龍蝦」協
