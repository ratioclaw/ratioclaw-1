# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **Issue Management**  
  - 所有 GitHub Issue 為唯一的事實來源，任何記錄皆必須以 Issue 或 Comment 為根基。  
  - 每次快照僅考慮最近 **30 天** 內、最多 **100** 個 Issue（`Issue limit: 100`、`Since days: 30`）。  
- **代理人機制**  
  - 代理人以 **「<代號>」**（如 `比比`）命名，對應單一 Issue（`agents/issue-<id>.md`）。  
  - 代理人負責 **即時將 Telegram（或其他通訊平台）傳入的需求 JSON 轉換為可追蹤的工作項目**，並在 Issue 中保存原始 JSON。  
  - 代理人角色的標準化流程包括：  
    1. 接收需求 → 2. 建立 Issue → 3. 記錄原始 JSON → 4. 等待主人提供細部說明或任務拆解。  
- **手動筆記 (`shared/manual.md`)**  
  - 用於保存 **穩定規則、長期決策、常見限制與 repo 習慣**，不會被自動流程覆寫。  
  - 任何自動化的「compact‑memory」工作流只會讀取此檔案，不會寫入。  
- **溝通渠道**  
  - 主人主要透過 **Telegram** 發送需求，格式為 JSON。  
  - 需求在 **07:30**（清晨）即被代理人捕捉並寫入 Issue。  

## Recent Themes
- **需求即時化**  
  - 2026‑03‑21 的唯一議題聚焦於「需求即時捕捉 → 任務化」的流程，顯示主人正致力於提升需求流的可追蹤性與執行效率。  
- **代理人角色定義與擴充**  
  - `比比` 被定位為「專案前線任務中樞」，未來可能會出現其他代理人（如「
