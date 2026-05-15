# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶保存機制**：每日由多個 issue agents 讀取過去 30 天內（上限 100 件）的 GitHub Issue 與 Comment，將摘要寫入 daily snapshot。若當日無可用 Issue，agents 只保留既有記憶，不會自行產生新條目。  
- **共通規則**  
  1. **原始資料來源** 必須是 Issue 或 Comment，任何手動筆記僅作為輔助說明，**不會被覆寫**。  
  2. **跨 Issue 主題** 只在多個 Issue 同時出現相同關鍵詞或情境時才會被抽取。  
  3. **決策紀錄** 只在有明確跨 Issue 共識時寫入；否則保持空白。  
  4. **Open Loops** 代表尚未結束或缺乏足夠資訊的待辦，會在後續 snapshot 中持續追蹤。  
- **已知長期風險**  
  - **知識孤島**：Legacy 系統中有一段只能由工程師 **柏宇** 解讀的「魔法 SQL」，若柏宇無法參與，相關維護與除錯將受阻。  
  - **時間估算挑戰**：在產品會議中突發的「緊急需求」揭露資深工程師對任務工時的估算常有偏差，需持續關注與改進。  

## Recent Themes
- **Issue #3 – 職涯導師**（狀態：Open）  
  - 自 2026‑04‑10 起未見新留言，仍有 **四項 active tasks** 在持續推進。  
  -
