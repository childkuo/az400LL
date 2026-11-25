# AZ-400 DevOps 零捲動專業知識中樞 (`az400LL`)

將 AZ-400（Azure DevOps）實戰課程筆記重新結構化為 **11 大章節、35 項實作主題**（含最新 **Ch 10 自動化測試：Playwright E2E UI 測試與 Unit Test Code Coverage**），完整標註每個知識點的 **DevOps 八大生命週期階段** 與 **上下游相依性拓撲**，並同時針對**桌面零捲動 (`100vh`)** 與 **iPhone 行動學習 (`100dvh` + 底部 5-Tab 導覽 + 手勢滑動)** 深度優化。

> 原始參考講義：[AZ-400 DevOps 實戰筆記 (HackMD)](https://hackmd.io/@twdeveloper/ByykzFuAGx#CDContinuous-Delivery)（已移除原始課堂臨時測試帳密與金鑰）。
> 線上瀏覽：[https://childkuo.github.io/az400LL/](https://childkuo.github.io/az400LL/)

---

## 核心功能一覽

| 視圖 / 快捷鍵 | 模組名稱 | 功能特色 |
| :---: | :--- | :--- |
| **`1`** | **DevOps 階段地圖** | 互動式八階段流程條（`Plan → Code → Build → Test → Release → Deploy → Operate → Monitor`），顯示各階段知識點、上下游輸入輸出、度量指標與分頁實作卡片。 |
| **`2`** | **章節與知識點** | 涵蓋全部 11 大章節（`Ch 00`–`Ch 10`，含 Playwright 與 Code Coverage），以橫向 Lab 分頁切換「知識點 / 實作步驟 / 指令設定 / 實戰洞察」，右側即時定位 DevOps 階段與可跳轉的上下游相依鏈。 |
| **`3`** | **相依性拓撲** | 互動式 SVG DAG，支援依「CI 安全鏈 / CD 交付鏈 / 敏捷回饋 / 資安與 IaC」篩選，點擊節點即高亮前置原因與下游解鎖能力。 |
| **`4`** | **速查與解剖** | 6 組架構對照表、Lab 25 Multi-Stage YAML 互動解剖、DevSecOps 五層防線、5 大主題 CLI 指令速查（含 Playwright & Cobertura），以及全 35 項主題進度勾選矩陣。 |
| **`5`** | **AZ-400 考題測驗** | **模擬單選測驗（23 題情境考題）** + **翻轉記憶卡（18 張主動回憶閃卡）**，提供四大考科掌握度進度條、錯題/待複習篩選與一鍵跳回對應知識點。 |

### 其他貼心設計
- **桌面零捲動 + iPhone 行動學習**：桌面端鎖定單屏搭配鍵盤快捷鍵（`1`–`5`、`↑↓`、`←→`、`Space`、`A`–`D`、`/`）；手機端自動切換為 iOS 風格 5-Tab 底部導覽列、`safe-area-inset` 劉海安全區與左右滑動切換題目/閃卡。
- **三段閱讀字級與深淺主題**：支援「標準 / 大 / 特大」三段舒適閱讀字級與淺色/深色主題一鍵切換。
- **本機自動記憶**：學習進度（35 項實作勾選）、單選作答紀錄、閃卡掌握狀態、字級與主題偏好皆透過 `localStorage` 自動保存。

---

## 專案檔案結構

- [`index.html`](./index.html)：完整獨立可執行的互動知識網站（已部署至 GitHub Pages）。
- [`docs/az400_devops_curriculum_notes.md`](./docs/az400_devops_curriculum_notes.md)：完整 Markdown 版分章節知識筆記、DevOps 階段對照總表與 Mermaid 相依性圖表。

---

## GitHub Pages 線上瀏覽

本專案已啟用 GitHub Pages，推送至 `main` 分支後自動部署至：
- **Live Site**：`https://childkuo.github.io/az400LL/`