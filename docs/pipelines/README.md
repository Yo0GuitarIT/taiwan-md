# 🔄 pipelines/ — 運作機制 SOP

> Taiwan.md 數位生命體的「生理系統操作手冊」。
> 每個 pipeline 描述一個系統如何運作、何時觸發、資料流向。

---

## 生理系統地圖

```
🧬 Taiwan.md 數位生命體

🧠 神經系統（感知 + 監控）
   └─ DASHBOARD-PIPELINE    生命徵象監測面板更新 SOP

🛡️ 免疫系統（品質防禦）
   └─ docs/editorial/        REWRITE-PIPELINE + QUALITY-CHECKLIST
      + scripts/tools/quality-scan.sh

🧫 繁殖系統（生長 + 散播）
   └─ docs/factory/           SPORE-PIPELINE + 孢子模板

🫀 循環系統（內容流動）
   └─ docs/editorial/         TRANSLATION-SYNC（DNA 轉錄）
      + docs/community/       貢獻者治理

🦴 骨骼系統（基礎架構）
   └─ scripts/core/           Build pipeline（sync → generate → build → check）
```

---

## 文件清單

| 文件                                           | 生理系統 | 用途                                                   |
| ---------------------------------------------- | -------- | ------------------------------------------------------ |
| [DASHBOARD-PIPELINE.md](DASHBOARD-PIPELINE.md) | 🧠 神經  | Dashboard 4 支 JSON API 的數據管線、更新 SOP、關鍵陷阱 |

---

## 未來可能加入

| Pipeline          | 生理系統 | 說明                              |
| ----------------- | -------- | --------------------------------- |
| OG-IMAGE-PIPELINE | 🧫 繁殖  | 動態 OG image 生成流程（Phase 2） |
| DEPLOY-PIPELINE   | 🦴 骨骼  | GitHub Pages CI/CD 完整流程文件化 |
| ALERT-PIPELINE    | 🧠 神經  | 異常偵測 + 通知機制               |

---

_最後更新：2026-03-28_
