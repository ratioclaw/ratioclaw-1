# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記錄方式**:  
  - 由每日 Issue Agent 產生的快照 (JSON) 供龍蝦群蒸餾長期記憶。  
  - 手動維護的 `shared/manual.md` 用於保存 **穩定規則、長期決策、常見限制與 repo 習慣**，不會被自動覆寫。  
- **工作流程**:  
  1. Issue / comment 為原始事實來源。  
  2. `compact‑memory` 讀取 `shared/manual.md` 以取得已確定的長期記憶。  
  3. 每日快照僅在有可用 Issue 時提供新資訊，否則保留既有記憶。  
- **目前觀測**: 2026‑05‑13 至 2026‑05‑19 的七天快照皆顯示「本次整理視窗沒有可用 issue」，代表近期 **無新 Issue** 產生或被標記為可用。

## Recent Themes
> 近期未偵測到跨 Issue 的共通主題。  
> 若未來出現持續出現的關鍵字或標籤，將在此節列出。

## Constraints
- **內容限制**  
  - 不得直接複製 Issue 原文於 `shared/manual.md`，僅保留抽象化、概括性的規則或決策。  
  - `compact‑memory` 只會讀取手動筆記，不會自行覆寫或刪除其中的條目。  
- **流程限制**  
  - 每日快照的 `Issue limit` 為 100，且僅檢視過去 30 天內的 Issue。  
  - 若快照期間無可用 Issue，系統會「保留既有記憶」而不產生新條目。  
- **不確定性**  
  - 目前缺乏足夠的 Issue 資料以驗證任何新規則或限制，故所有未在 `shared/manual.md` 中明確記載的假設皆視為 **未知**。

## Open Loops
- **待處理的 Issue**：目前無待處理的 Issue；需等待下一
