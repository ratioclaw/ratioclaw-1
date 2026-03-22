# Repository Memory  

## Stable Context  
- **核心工作流程**  
  - 以 GitHub Issue / Comment 為唯一原始資料來源，所有任務皆以 Issue 為單位追蹤。  
  - 代理人（🦞）依照 `agents/issue-{N}.md` 檔案記錄執行細節，並遵守 repo 內既定的 **coding‑agent** 工作流程 (`.github/workflows/coding-agent.yml`) 以及 **Copilot 解析腳本** (`.github/scripts/extract‑copilot‑result.mjs`)。  
  - 任何自動化排程皆透過 `schedule‑flow` 建立，排程 ID 必須在環境變數中註冊後方可執行。  

- **溝通管道**  
  - 主要與主人互動的介面為 Telegram Bot，代理人會即時將主人指令轉化為可追蹤的 Issue，並在完成後回覆文字或圖檔。  
  - 圖檔預設以 SVG 產出，若 Telegram 無法預覽，代理人會自動轉換為 PNG 並以 GitHub API 發佈於相關 Issue/PR。  

- **代理人角色與命名慣例**  
  - `比比`：負責文字類需求、教學說明、排程建立與 repo 掃描。  
  - `蝦趴`：負責圖形產出、格式轉換與即時回饋。  
  - 代理人名稱前置「🦞」以示身份，編號 (`#1`, `#2`) 與 Issue 編號保持一致。  

- **長期規則**  
  1. **不自行關閉 Issue**：除非主人明確指示，所有 Issue 均保持開啟狀態。  
  2. **環境變數必須先行設定**：任何排程或腳本執行前，相關環境變數必須在 repo 設
