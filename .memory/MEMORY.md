# Repository Memory

## Stable Context
- **記憶工作流程**  
  - 所有長期記憶皆以 **GitHub Issue / Comment** 為原始資料來源。  
  - 每日由 *issue agents* 產出 snapshot，彙整當天活躍的 Issue，並以 **deterministic** 演算法產生摘要。  
  - `compact‑memory` 工作流會讀取本手動筆記（`shared/manual.md`），但 **不會覆寫**，因此此檔案僅作為「穩定規則」與「共識」的存放處。  
  - 每次 snapshot 只保留最近 30 天、最多 100 個 Issue 的資訊；若期間無可用 Issue，則保留既有記憶不變。

- **共通慣例**  
  - **不直接複製** Issue 原文於長期記憶檔案；僅抽取概念、決策、未完成事項等可重用資訊。  
  - **四大區塊**（Stable Context、Recent Themes、Constraints、Open Loops）是龍蝦群對主人記憶的固定呈現格式。  
  - 所有新發現的跨 Issue 主題、決策或限制，皆應先歸類於 **Recent Themes**，待觀察足夠次數後再遷入 **Stable Context**。

- **技術參數**（供工程參考）  
  - Repository: `ratioclaw/ratioclaw-1`  
  - Snapshot 產生時間皆為 UTC，格式 `YYYY‑MM‑DDTHH:MM:SS.sssZ`。  
  - 使用的摘要來源標示為 `deterministic`，表示結果可重現且不受隨機因素影響。

## Recent Themes
> 目前的每日快照（2026‑11‑12 至 2026‑11‑19）皆顯示 **「本次整理視窗沒有可用 issue」**，因此未偵測到任何跨 Issue 主題或重複出現的議題。  
- **缺乏活躍 Issue**：連續 8 天無新 Issue 被標記為「可用」，暗示目前開發或維運工作可能處於靜止、等待需求或是已完成主要任務。  
- **等待更新**：所有快照的 **Open Loops** 都寫著「等待下一輪 issue 更新後再整理」，這是唯一可觀察到的近期共通訊息。

> 若未來出現新 Issue，請留意是否出現以下常見主題：
> - 功能需求變更  
> - Bug 修復流程  
> - CI/CD 設定調整  

## Constraints
- **資訊
