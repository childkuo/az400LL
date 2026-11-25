# AZ-400 DevOps 零捲動專業知識中樞 (`az400LL`)

將 AZ-400（Azure DevOps）實戰課程筆記重新結構化為 **10 大章節、32 項實作主題**，完整標註每個知識點的 **DevOps 八大生命週期階段** 與 **上下游相依性拓撲**，並封裝成一套**完全免上下捲動（`100vh` 鎖定視窗）**的互動式單頁專業知識網站。

> 原始參考講義：[AZ-400 DevOps 實戰筆記 (HackMD)](https://hackmd.io/@twdeveloper/ByykzFuAGx#CDContinuous-Delivery)（已移除原始課堂臨時測試帳密與金鑰）。

---

## 核心功能一覽

| 視圖 / 快捷鍵 | 模組名稱 | 功能特色 |
| :---: | :--- | :--- |
| **`1`** | **DevOps 階段地圖** | 互動式八階段流程條（`Plan → Code → Build → Test → Release → Deploy → Operate → Monitor`），顯示各階段知識點、上下游輸入輸出、度量指標與 2×2 分頁實作卡片。 |
| **`2`** | **章節與知識點** | 左側固定顯示全部 10 大章節（`Ch 00`–`Ch 09`），中央以橫向 Lab 分頁切換「核心知識點 / 實作步驟 / 設定指令」，右側即時定位 DevOps 階段與可跳轉的上下游相依鏈。 |
| **`3`** | **相依性拓撲** | 互動式 SVG DAG，支援依「CI 品質安全鏈 / CD 發布交付鏈 / 敏捷回饋閉環 / 資安與 IaC 鏈」篩選，點擊節點即高亮前置原因與下游解鎖能力。 |
| **`4`** | **速查與解剖** | 6 組架構對照表、Lab 25 Multi-Stage YAML 互動解剖、DevSecOps 五層防線、高頻 CLI 指令速查，以及全 32 項主題進度勾選矩陣。 |
| **`5`** | **AZ-400 考題測驗** | **模擬單選測驗（20 題情境考題）** + **翻轉記憶卡（16 張主動回憶閃卡）**，提供四大考科掌握度進度條、錯題/待複習篩選與一鍵跳回對應知識點。 |

### 其他貼心設計
- **零捲動單屏工作台**：全程鎖定視窗高度，搭配分頁與鍵盤快捷鍵（`1`–`5` 切視圖、`↑↓` 切章節、`←→` 切換題目/Lab、`Space` 勾選完成或翻轉記憶卡、`A`–`D` 直接作答、`/` 快速搜尋）。
- **本機自動記憶**：學習進度（32 項實作勾選）、單選作答紀錄、閃卡掌握狀態與淺色/深色主題皆透過 `localStorage` 自動保存。

---

## 專案檔案結構

- [`index.html`](./index.html)：完整獨立可執行的零捲動互動知識網站（可直接部署至 GitHub Pages 或本機瀏覽器開啟）。
- [`docs/az400_devops_curriculum_notes.md`](./docs/az400_devops_curriculum_notes.md)：完整 Markdown 版分章節知識筆記、DevOps 階段對照總表與 Mermaid 相依性圖表。

---

## 啟用 GitHub Pages 線上瀏覽

1. 前往本 Repository 的 **Settings → Pages**。
2. 於 **Build and deployment → Source** 選擇 **Deploy from a branch**。
3. Branch 選擇 `main`、資料夾選擇 `/ (root)` 後點選 **Save**。
4. 數十秒後即可於 `https://childkuo.github.io/az400LL/` 直接線上瀏覽！