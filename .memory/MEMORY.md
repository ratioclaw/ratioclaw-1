# Repository Memory

## Stable Context
- **倉庫名稱**：`ratioclaw/ratioclaw-1`  
- **記憶來源層級**  
  1. **GitHub Issue / Comment**：所有原始事實與決策皆以 Issue 為唯一真實來源。  
  2. **Shared Manual Notes (`shared/manual.md`)**：由人類手動維護的長期規則、決策與限制。  
  3. **Daily Snapshots**：由各 Issue Agent 每日彙整的摘要，用於捕捉近期變化。  
- **工作流程**  
  - `compact-memory workflow` 會讀取 `shared/manual.md` 作為「穩定記憶」的基礎，**不會覆寫**此檔。  
  - 每日快照只在有可用 Issue 時產生摘要，若無則保留既有記憶。  
- **已知的長期規則（來自手動筆記）**  
  - **不複製完整 Issue 文字**：手動筆記僅列出規則、決策與限制，避免冗長。  
  - **手動筆記是唯一的長期記憶檔**：自動化流程只會讀取，不會寫入。  
  - **Issue 為唯一事實來源**：所有新事實、決策與待辦必須先在 Issue 中產生，才能被快照捕捉。  

## Recent Themes
- **近期無可辨識跨 Issue 主題**：2026‑08‑15 至 2026‑08‑21 的每日快照皆顯示「本次整理視窗沒有可用 issue」且未偵測到跨 Issue 主題。  
- **持續的空白狀態**：連續七天（含今天）皆未出現新 Issue，說明目前倉庫處於靜止或維護階段。  

## Constraints
- **資料來源限制**  
  - 只能從 **GitHub Issue / Comment** 取得原始資訊。  
  - `shared/manual.md` 只能作為手動維護的長期記憶，不得自動覆寫。  
- **快照參數**（雖非硬性限制，但影響記憶範圍）  
  - **Issue limit**：最多 100 件 Issue 會被納入每日快照。  
  - **Since days**：僅檢視最近 30 天內的 Issue。  
- **內容呈現規則**  
  - 不直接複製
