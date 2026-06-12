# naval-skill-zh-tw 開發計畫

> 最後更新：2026-06-12
> 專案狀態：繁中台灣版 v1.0 改編完成、repo 已 public 並接 CTA 導流，主動推廣等 2026-08 進階課 launch 時啟動

---

## Phase 0：繁體中文台灣版改編 ✅

- [x] Fork 花叔（alchaincyf/naval-skill）原版，保留 MIT 授權與原作者署名
- [x] 簡體 → 繁體全文轉換（SKILL.md / README.md / references / examples）
- [x] 中國用詞 → 台灣慣用詞（軟體／程式／共同創辦人／行事曆／賽局理論／部落格／否證主義）
- [x] 保留 Naval 英文金句原貌，心智模型、修辭結構、調研來源完全保留
- [x] README CTA 改為三層導流（迷你課直購 / 雷蒙週報 / 進階課 waitlist）

**重要發現**：
- 改編定位是「把花叔的好東西帶給繁中圈」，不是「做更好的版本」——所有對外文案都要尊重原作者
- 課程素材同步存在 `600_Project/ai-bootcamp/content/ch3/skills/naval-tw/`（課程 Ch3「萃取知識」的示範素材）

---

## Phase 1：公開推廣（waiting，2026-08 課程 launch 時啟動）

- [ ] 等進階課（AI Agent x 超級個體進階陪跑課）開始對外推廣時集中火力 launch（約 2026-07-25 至 2026-08-05）
- [ ] 自有平台：Threads 長串文、FB 長文、雷蒙週報深度文章、raymondhouch.com 文章、Discord 社群預告
- [ ] 致意原作者花叔：X @AlchainHust 致謝、B 站留言、GitHub Discussions 告知繁中版
- [ ] AI / Skill 圈：awesome-claude-code 清單 PR、台灣論壇分享
- [ ] 配套素材：3-5 段雷蒙親跑的使用範例、「萃取知識」1 分鐘短影片、進階課 landing page waitlist

**決策邏輯**：提前推廣的流量現在沒有課程接住、會攤薄轉換力道，所以留到課程上線時單一 launch 動作集中火力。完整清單見關聯文件。

---

## 技術備註

- 語言 / 框架：純 Markdown Claude Code Skill（`SKILL.md` + `references/` + `examples/`），無程式碼、無建置流程
- 安裝方式（使用者端）：`npx skills add` 或手動複製 SKILL.md 到 Claude Code skills 目錄
- 部署：無需部署，GitHub public repo 即是發佈管道（`github.com/Raymondhou0917/naval-skill-zh-tw`）
- 更新方法：直接改 Markdown → commit → `git push origin`（main branch 即對外版本）
- 授權：MIT（沿用原版），可被 fork / 改 / 用

## 關聯文件

- `../100_Todo/projects/2026-08_Naval-Skill-公開推廣.md`（vault 內路徑：`100_Todo/projects/2026-08_Naval-Skill-公開推廣.md`）：完整推廣 TODO、觸發時機、成效指標
- `README.md`：對外介紹、效果示例、三層 CTA
- 原作者花叔：https://github.com/alchaincyf/naval-skill
