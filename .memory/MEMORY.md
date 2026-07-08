# Repository Memory

## Stable Context
- **Issue‑driven記憶**：所有原始資訊皆來自 GitHub Issue 與其評論，這是唯一可信的事實來源。  
- **手動筆記的角色**：`shared/manual.md` 用於保存長期穩定規則、決策、常見限制與 repo 習慣，**不會被自動流程覆寫**。  
- **compact‑memory 工作流**：會讀取 `shared/manual.md` 以取得「長期記憶」框架，但不會將其內容直接寫回；自動產出的每日快照只會**蒸餾**出可重用的概念。  
- **蒸餾原則**：  
  1. 只保留**抽象規則**或**可重用的上下文**，避免逐段複製原始 Issue。  
  2. 若資訊僅在單一天出現且未形成穩定事實，則歸入「Open Loops」或「Recent Themes」而非「Stable Context」。  
- **repo 習慣**：  
  - 所有新議題必須以 Issue 形式提出，並在標籤 (`label`) 中標明優先度與類別。  
  - 每日快照只在有可用 Issue 時才會產生新內容，否則保留既有記憶。  

## Recent Themes
- **2026‑07‑02 ~ 2026‑07‑08**：連續七天的每日快照皆顯示「本次整理視窗沒有可用 issue，先保留既有記憶」。  
- **跨 Issue 主題**：無法辨識任何
