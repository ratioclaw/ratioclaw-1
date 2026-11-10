# Repository Memory

## Stable Context
- **記憶流程**：本倉庫的長期記憶由兩大來源構成  
  1. **Shared Manual Notes**（`shared/manual.md`）— 由人類手動維護，保存穩定規則、長期決策、常見限制與 repo 習慣。  
  2. **Daily Snapshots**（`daily/*.json`）— 由當天活躍的 issue agents 彙整，僅在有可用 issue 時產生跨 issue 主題、決策與開放環節。  
- **資料來源原則**：所有具體事實皆必須來自 GitHub Issue 或 Comment；`shared/manual.md` 只作為摘要與指引，**不會被自動覆寫**。  
- **記憶更新節奏**：每日快照會檢查過去 30 天內的 issue；若無可用 issue，則保留既有記憶，不產生新條目。  
- **工程可讀性**：本文件僅保留 **抽象化、可重用** 的上下文資訊，避免逐段複製原始日誌或 issue 標題。

## Recent Themes
> 目前的每日快照（2026‑11‑03 至 2026‑11‑10）皆未偵測到可用 issue，故 **無可辨識的跨 issue 主題**。  
- **暫無重複出現的主題**。  
- 若未來出現持續性的議題（例如「測試自動化」或「部署流程」），將在此節匯總。

## Constraints
1. **來源限制**：只能引用 Issue / Comment 作為事實依據；`shared/manual.md` 只能作為規則與限制的描述。  
2. **不可覆寫**：自動化流程（如 `compact-memory`）不會改寫 `shared/manual.md`，因此任何手動加入的規則必須保持一致性。  
3. **資訊稀疏**：當前 30 天內無任何開放或已關閉的 issue，導致缺乏新資訊供記憶蒸餾。  
4. **不確定性聲明**：若未來出現相互矛盾的資訊，需在本節標註「不確定」或
