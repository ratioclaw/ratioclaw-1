# Repository Memory

## Stable Context
- **記憶來源**：所有長期記憶皆以 GitHub **issue** 與 **comment** 為唯一原始資料來源。  
- **記憶整理流程**：每日由各 issue agents 產出 *daily snapshot*，彙整當天活躍 issue，之後由龍蝦群蒸餾成可重用的長期記憶。  
- **手動筆記**：`shared/manual.md` 為人類手動維護的長期記憶檔案，僅保存 **穩定規則、長期決策、常見限制與 repo 習慣**，不會被自動流程覆寫。  
- **compact‑memory workflow**：會讀取 `shared/manual.md` 以取得上下文，但不會寫回或改寫此檔。  
- **記憶原則**：  
  1. **不直接複製** issue 原文；只抽取概念、規則或決策。  
  2. **避免冗餘**：相同資訊只保留一次，避免日誌逐段搬移。  
  3. **工程可讀性**：使用 Markdown 結構、清晰標題與條列，方便程式與人類檢索。  

## Recent Themes
- **2026‑11‑14 至 2026‑11‑21**：每日 snapshot 均顯示「本次整理視窗沒有可用 issue」，因此 **未偵測到跨 issue 主題、決策或新標籤**。  
- **Open Loop 狀態**：所有天數皆列出「等待下一輪 issue 更新後再整理」，顯示目前的工作流正處於 **待命** 狀態。  

## Constraints
- **資料完整性**：除非有新的 issue 出現，否則不應自行創建或推測長期規則。  
- **資訊來源限制**：只能引用 `shared/manual.md` 與每日 snapshot 中的明確資訊；若資訊不足或相互矛盾，必須標註不確定性。  
- **更新頻率**：記憶只能在有 **可用 issue** 時更新；若連續多日無 issue，保持現有記憶不變。
