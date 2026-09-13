# Repository Memory

## Stable Context
- **記憶管理原則**  
  - 只以 GitHub Issue / Comment 為原始資料來源，任何長期記憶皆須根據這些來源抽象、濃縮。  
  - `shared/manual.md` 為人工維護的長期記憶檔，**不會**被自動流程覆寫，僅供參考與補充。  
  - 產出 `MEMORY.md` 時必須避免逐段複製原始 Issue 文字，必須將資訊蒸餾成可重用的規則或事實。  

- **Repo 內部慣例**  
  - 所有 agents 必須遵守「compact‑memory workflow」：  
    1. 讀取 `shared/manual.md` 取得穩定規則與限制。  
    2. 從每日快照中萃取跨 Issue 主題與決策。  
    3. 只在確定為長期事實時寫入 **Stable Context**，其餘暫時放入 **Recent Themes** 或 **Open Loops**。  
  - 每日快照若無可用 Issue，則保留既有記憶，不新增或刪除任何條目。  

- **目前已確認的長期事實**  
  - 近期 2026‑09‑07 至 2026‑09‑13 的所有每日快照皆顯示「本次整理視窗沒有可用 issue」，因此 **目前沒有任何活躍的 Issue**。  
  - 因無活躍 Issue，**沒有跨 Issue 主題、決策或待辦事項** 可被納入長期記憶。  

## Recent Themes
- **缺乏活躍 Issue**：連續七天（2026‑09‑07 ~ 2026‑09‑13）皆未偵測到可用 Issue，系統持續保留既有記憶。  
- **等待更新**：每日快照的 **Open Loops** 均寫明「等待下一輪 issue 更新後再整理」，顯示目前的工作焦點是監控 Issue 流入。  

> **註**：上述主題屬於短期觀測，尚未形成穩定規則，
