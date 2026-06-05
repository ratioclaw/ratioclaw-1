# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶模型**：以 GitHub Issue / Comment 為唯一原始資料來源，日常快照由各 issue agents 於 30 天內的活躍 issue 生成。  
- **手動筆記 (`shared/manual.md`)**：保存長期穩定規則、決策、限制與 repo 習慣，**不會被自動流程覆寫**。  
- **Compact‑Memory 工作流程**：  
  1. 讀取 `shared/manual.md` 作為基礎上下文。  
  2. 依據每日快照蒸餾出可重用的長期記憶。  
  3. 只保留抽象化、可重用的資訊，避免逐段複製原始 issue 文字。  
- **目前觀測**：過去 7 天（2026‑05‑30 至 2026‑06‑05）皆未偵測到可用的 issue，故沒有新增的跨 issue 主題、決策或標籤。  

> **不確定性**：除上述流程與手動筆記外，缺乏其他可驗證的長期規則或決策。若未來出現新 issue，相關資訊將補充於此。

## Recent Themes
- **無可辨識跨 Issue 主題**：每日快照皆報告「目前沒有可辨識的跨 issue 主題」。
- **持續無 Issue 活動**：連續七天皆顯示「本次整理視窗沒有可用 issue」，暗示近期開發或討論活動較少。

## Constraints
1. **不複製完整 Issue 原文**：手動筆記僅保留抽象規則與決策，原始 Issue 文字僅供 agents 內部參考。  
2. **手動筆記不可被自動覆寫**：`shared/manual.md` 只作為長期記憶的「只讀」來源。  
3. **每日快照上限**：每次快照最多處理 100 個 issue，且僅限最近 30 天內的活躍 issue。  
4. **資訊蒸餾原則**：只保留可重用、穩定的上下文；臨時或單日出現的資訊應歸入「Open Loops」或「Recent Themes」而非「Stable Context」。  

## Open Loops
- **等待 Issue 更新**：
