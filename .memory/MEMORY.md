# Repository Memory

## Stable Context
- **Repository**: `ratioclaw/ratioclaw-1`  
- **記憶來源**  
  - 主要以 GitHub **issue / comment** 為原始資料。  
  - `shared/manual.md` 為人工維護的長期記憶，僅保存 **穩定規則、長期決策、常見限制、repo 習慣**，不會被自動流程覆寫。  
- **工作流程**  
  - 每日快照 (`daily/*.json`) 由各 issue agents 產出，蒐集過去 30 天內的 issue。  
  - 若快照中找不到可用 issue，則保留既有記憶，不會產生新條目。  
- **共通慣例**  
  - **不** 直接複製 issue 原文於長期記憶；只抽象化為規則或決策。  
  - **compact‑memory workflow** 會讀取 `shared/manual.md`，但不會修改它。  

> **不確定性**：目前未觀測到任何跨 issue 主題、決策或持續的工作項目，故上述內容即為唯一可確認的穩定資訊。

## Recent Themes
- **無可辨識的跨 issue 主題**（2026‑10‑28 至 2026‑11‑04 的所有快照皆未偵測到）。  
- **每日快照皆顯示「本次整理視窗沒有可用 issue」**，表示近期內 repository 內缺乏活躍的 issue。  

## Constraints
1. **資料來源限制**  
   - 只能依賴 GitHub issue / comment 作為事實依據；若缺乏此類資料，則不應推測新規則。  
2. **記憶編寫原則**  
   - 避免逐段複製原始日誌或 issue 文字。  
   - 必須將資訊抽象為「規則」或「決策」後再寫入長期記憶。  
3. **更新時機**  
   - 只有在新 issue 出現或現有 issue 有變更時，才觸發記憶的增補或調整。  

## Open Loops
- **等待新 Issue**：目前所有快照皆顯示「等待下一輪 issue 更新後再整理」。需持續監控 repository，待有新 issue 時重新評估跨 issue 主題與決策。  
-
