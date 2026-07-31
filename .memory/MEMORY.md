# Repository Memory

## Stable Context
- **長期規則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何摘要或記憶皆須根據這些原始訊息產生。  
  - `shared/manual.md` 為人工維護的長期記憶檔案，**不會被自動流程覆寫**，僅供參考與補充。  
  - 任何自動化的 `compact‑memory` 工作流會 **讀取** 但 **不會寫入** `shared/manual.md`。  
  - 產出給外部使用者的記憶檔（如本 `MEMORY.md`）必須 **避免直接複製** Issue 原文，僅保留關鍵概念與決策。  

- **長期決策**  
  - 目前尚未在 Issue 中形成跨議題的決策，故無固定的長期策略可記錄。  

- **共通限制**  
  - 若缺乏可用 Issue，系統必須保留既有記憶，**不新增** 推測或臆測的資訊。  
  - 所有記憶內容必須保持 **工程可讀性**，即使以「龍蝦」的口吻敘述，也要讓程式開發者易於理解與追蹤。  

- **Repo 習慣**  
  - 每日快照 (`daily/*.json`) 會在 **UTC+0 20:xx** 時間點產出，涵蓋過去 30 天內的 Issue 活動。  
  - 快照的結構固定為：Agent Activity、Cross‑Issue Themes、Decisions、Open Loops、Top Labels。  
  - 當快照顯示「本次整理視窗沒有可用 issue」時，代表 **Issue 列表為空**，系統僅保留先前的記憶。  

## Recent Themes
> 近期（過去 7 天）未偵測到任何跨 Issue 的共通主題或重複出現的議題。所有快照皆報告「目前沒有可辨識的跨 issue 主題」。

## Constraints
1. **資訊來源限制**：只能從 Issue / Comment 抽取事實，手動筆記僅作為補充。  
2. **避免重複**：不應將每日快照的逐段文字搬入本文件，必須進行 **蒸餾**（抽象化）後再呈現。  
3. **不確定性標示**：若資訊不足或相互矛盾，
