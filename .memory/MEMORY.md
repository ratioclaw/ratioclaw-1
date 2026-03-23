# Repository Memory  

## Stable Context  

- **Telegram ↔ GitHub 自動化工作流**  
  - 由「比比」負責將 Telegram 群組/頻道的需求訊息即時轉換為 GitHub Issue 或 Project 卡片，並自動加標籤、指派負責人。  
  - 相關腳本與工作流程已在 `.github/workflows/coding-agent.yml`、`.github/scripts/extract‑copilot‑result.mjs`、`workspaces/issue-{N}/` 中實作，支援 Copilot CLI 輸出解析。  

- **每日 AI 新聞推播排程**  
  - 透過 `schedule‑flow` 建立的排程（ID `sch_3bb0b6be67ff4b38815b12ca6504342e`）每天於 09:00 觸發，會掃描整個 repo，回報 Copilot CLI 的呼叫方式與範例。  

- **圖檔即時交付規範**  
  - 由「蝦趴」負責產出視覺資產。因 Telegram 無法直接預覽 SVG，必須在 PR/Issue 中以 PNG 形式貼圖，並提供 raw URL。  

- **共通限制與慣例**  
  - 所有原始需求與討論必須以 GitHub Issue 為唯一真相來源，Telegram 只作為前端觸發點。  
  - 任何自動化功能在「需求規劃」階段必須先確定 **Bot API 選型、訊息格式規範、錯誤回報機制**，方可進入開發。  
  - 變更或新增功能需在 Issue 中留下完整文字紀錄，避免僅依賴即時聊天訊息。  

## Recent Themes  

| 主題 | 近期觀察 | 影響 |
|------|----------|------|
| **即時回饋機制** | 3 天內「比比」與「蝦趴」皆在 Telegram 中即時回應主人需求（文字需求 → Issue、SVG → PNG） | 強化了「需求即時可視化」的使用者體驗，成為自動化流程的核心價值。 |
| **資金需求與變現方案** | 3/21 針對「急需 1,000,000 台幣」提出 **借、賣、預收** 三條
