# AZ-400 DevOps 互動教學學院 (`az400LL`)

將 AZ-400（Azure DevOps）實戰課程重新結構化為**「一章節一課堂」**的互動式教學網站，涵蓋 **11 大章節（`Ch 00`–`Ch 10`）、38 項可勾選學習目標、45 個核心知識點詳解與 35 項實作演練**（已同步最新 **Playwright 自動化 UI 測試**與 **Unit Test Code Coverage**）。

> 原始參考講義：[AZ-400 DevOps 實戰筆記 (HackMD)](https://hackmd.io/@twdeveloper/ByykzFuAGx#CDContinuous-Delivery)（已移除原始課堂臨時測試帳密與金鑰）。
> 線上教學首頁：[https://childkuo.github.io/az400LL/](https://childkuo.github.io/az400LL/)
> 舊版零捲動知識中樞（保留並存）：[https://childkuo.github.io/az400LL/portal.html](https://childkuo.github.io/az400LL/portal.html)

---

## 每章固定五段式教案設計

| 區塊 | 教學內容 | 學習體驗特色 |
| :---: | :--- | :--- |
| **`01`** | **本章主題與實務定位** | 拆解「這章在學什麼？」與「為什麼實務上很重要？」，標示 DevOps 八大階段定位與上下游章節跳轉。 |
| **`02`** | **學習目標** | 每章提供 3–4 條具體可衡量的學習目標（全課程共 38 項），支援點擊勾選達成並自動儲存於本機。 |
| **`03`** | **核心知識點詳解** | 結構化拆解全課程 45 個核心觀念，附分類標籤、原理說明、「重點精華」一句話總結與講師避坑提醒。 |
| **`04`** | **實作演練與關鍵指令** | 收錄全 35 項 Lab 步驟清單與一鍵複製的 CLI / YAML / Bicep / C# 指令，支援逐項勾選實作完成。 |
| **`05`** | **本章隨堂檢核** | 各章底部直接內嵌對應的 AZ-400 情境單選題與重點翻轉記憶卡，立即驗收學習成效。 |

### 其他學習輔助功能
- **三大模式切換**：**章節教學**（左側四階段目錄 + 右側閱讀主欄）、**課程大綱 (11 章全覽)**、**全課程模擬測驗**（23 道情境單選 + 18 張主動回憶閃卡）。
- **桌面與 iPhone 雙端優化**：手機端提供側滑章節抽屜、底部上一章／下一章固定導覽與劉海安全區適配。
- **閱讀字級與深淺主題**：支援「標準 / 大 / 特大」三段字級切換、淺色／深色主題與 `/` 快速全文搜尋，所有學習進度皆由 `localStorage` 自動記憶。

---

## 專案檔案結構

- [`index.html`](./index.html)：新版「一章節一課堂」互動教學網站（GitHub Pages 主首頁）。
- [`portal.html`](./portal.html)：原版桌面零捲動五視圖知識中樞（保留供快速對照與 SVG DAG 檢視）。
- [`docs/az400_devops_curriculum_notes.md`](./docs/az400_devops_curriculum_notes.md)：完整 Markdown 版分章節知識筆記、DevOps 階段對照總表與 Mermaid 相依性圖表。

---

## GitHub Pages 線上瀏覽

- **新版章節教學網站**：`https://childkuo.github.io/az400LL/`
- **原版零捲動知識中樞**：`https://childkuo.github.io/az400LL/portal.html`