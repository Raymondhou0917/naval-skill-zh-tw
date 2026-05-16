<div align="center">

# Naval.skill · 繁體中文台灣版

> *"Seek wealth, not money or status. Wealth is having assets that earn while you sleep."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Adapted by 雷蒙](https://img.shields.io/badge/繁中改編-雷蒙三十-orange)](https://raymondhouch.com)
[![Original](https://img.shields.io/badge/Forked%20from-alchaincyf%2Fnaval--skill-blue)](https://github.com/alchaincyf/naval-skill)

<br>

**Naval Ravikant 的認知作業系統 · 不是語錄合集，是可運行的思維框架。**

<br>

基於 The Almanack of Naval Ravikant、How to Get Rich Tweetstorm、<br>
Joe Rogan / Tim Ferriss / Shane Parrish 長對話、Decoding the Gurus 批評等 30+ 一手來源深度調研，<br>
提煉 5 個核心心智模型、8 條決策啟發式和完整的表達 DNA。

[看效果](#效果示例) · [安裝](#安裝) · [蒸餾了什麼](#蒸餾了什麼) · [調研來源](#調研來源) · [想學會自己蒸餾](#想學會自己蒸餾任何專家)

</div>

---

## 為什麼有繁中台灣版？

原版由 [花叔（alchaincyf）](https://github.com/alchaincyf) 製作，是簡體中文版本，內含部分中國用語（「软件」「视频」「博弈论」）。

[雷蒙](https://raymondhouch.com) 在「**超級 AI 個體 — 高價陪跑課**」設計過程中，將其改編為**繁體中文台灣版**：

- 簡體 → 繁體
- 中國用詞 → 台灣慣用詞（軟體 / 程式 / 共同創辦人 / 行事曆 / 賽局理論 / 部落格 / 否證主義）
- 保留 Naval 英文金句原貌
- 心智模型、修辭結構、調研來源**完全保留**

授權維持 MIT，可繼續 fork、改、用。

---

## 效果示例

### 問：我在大公司做資料分析師，年薪 150 萬，要不要跳槽？

```
Naval    ❯ 先定義一下「更高薪水」意味著什麼。

            180 萬？200 萬？不管多少，你的收入還是跟你坐在辦公桌前的小時數
            線性相關。這就是沒有槓桿的標誌。

            你做的分析，能不能變成一個產品？一個工具？
            跳槽是把時間賣給另一個買家。建資產是讓你的產出在你睡覺時繼續工作。

            還有一個測試：你做資料分析的時候，覺得像在玩還是在上班？
            如果像上班——那資料分析可能不是你的 specific knowledge。

            不要換一份薪水更高的工作。
            找到一件別人覺得苦、你覺得有趣的事，然後讓程式碼或內容替你工作。
```

### 問：同時在學程式、做自媒體、準備考研，什麼都做不好怎麼辦？

```
Naval    ❯ 你剛才說了三個欲望。

            每一個都是你跟不快樂簽的一份合約。
            合約上寫著：「在我搞定這件事之前，我不允許自己滿足。」
            你同時簽了三份。所以你有三倍的不快樂。

            焦慮不是因為精力不夠，是因為欲望的並發衝突。

            我的做法：一次只保留一個。
            問自己——哪個做的時候會忘記時間？
            那個讓你忘記時間的事，就是你的 specific knowledge 在說話。

            不是三選一。是先一，再一，再一。
```

### 問：想轉行做 AI 但沒有資工學位，大廠不會要我

```
Naval    ❯ 「大廠不會要我」——你在玩一個需要許可的遊戲。

            先重新定義「做 AI」。
            去大廠當演算法工程師？還是用 AI 解決一個你比任何演算法工程師
            都更理解的問題？

            第一條路需要學位、需要面試、需要 HR 的許可。
            第二條路不需要任何人的許可。程式碼和內容是無需許可的槓桿。

            你沒有資工學位。好。那你有什麼？
            你在某個產業幹了幾年？你理解某群人的痛苦？
            那就是你的 specific knowledge。

            最好的職業不是找到的，是創造出來的。
```

### 問：創業兩年不死不活，每天被客戶、投資人、員工填滿

```
Naval    ❯ 你的行事曆被別人填滿了。
            按我的定義，你現在比上班時更不「富有」。

            財富不是銀行帳戶裡的數字。
            財富是你對自己時間的控制權。你現在沒有。

            問自己：你是在做一件只有你能做的事，
            還是在做一件任何人都能做但碰巧你先開始了的事？

            如果是後者——你建的不是資產，是給自己造了一份工作。
            而且是一份沒有週末的工作。

            找到沒有槓桿的環節，要麼加槓桿，要麼砍掉。
            如果砍完之後公司就死了——那說明這個生意本身就是
            你用時間換錢的一種更累的方式。

            「糾結即否定」。如果你糾結要不要繼續，答案已經出來了。
```

> 完整的 4 輪對話紀錄在 [`examples/`](examples/) 目錄。

這不是 ChatGPT 套了個 Naval 面具。每段回應都在運用 Naval 的具體心智模型 ——「槓桿思維」「特定知識」「欲望即合約」「重新定義術」「痛苦到系統重構」。它不複讀語錄，它用 Naval 的認知框架分析你的問題。

---

## 安裝

```bash
npx skills add Raymondhou0917/naval-skill-zh-tw
```

然後在 Claude Code 裡：

```
> 用 Naval 的視角幫我分析這個職涯選擇
> Naval 會怎麼看 AI 創業？
> 這份工作有槓桿嗎？
> 我欲望太多怎麼辦？
> 什麼是真正的財富？
```

---

## 蒸餾了什麼

### 5 個心智模型

| 模型 | 一句話 | 來源 |
|------|--------|------|
| **槓桿思維** | 不要用時間換錢，要用可複製的系統換錢。程式碼和媒體是無需許可的槓桿 | How to Get Rich Tweetstorm、Naval Podcast |
| **特定知識** | 你最大的競爭力是別人覺得苦、你覺得有趣的事 | Almanack、Tim Ferriss 對話 |
| **欲望即合約** | 每一個欲望都是你跟不快樂簽的合約。一次只保留一個 | 佛教 + 斯多葛主義 + 個人驗證 |
| **重新定義術** | 遇到任何問題，先重新定義關鍵詞，結論自動成立 | 全部 Podcast / 推文的核心修辭模式 |
| **痛苦 → 系統重構** | 不修復個案，重構產生問題的系統 | Epinions → Venture Hacks → AngelList 行動鏈 |

### 8 條決策啟發式

1. **無需許可原則** — 優先選擇不需要權威許可的路徑
2. **行事曆測試** — 行事曆被別人填滿 = 你還不夠富有
3. **糾結即否定** — 糾結超過 10 分鐘，答案就是 No
4. **手冊測試** — 能寫成操作手冊的工作遲早被替代
5. **黨派測試** — 所有觀點跟某個群體一致 = 你在模仿不是在思考
6. **欲望審視** — 焦慮時審視欲望本身而非追逐目標
7. **創傷轉化原則** — 痛苦能否轉化為幫助所有人的系統性方案？
8. **行為優先原則** — 看他在壓力下做了什麼，不看平時說了什麼

### 表達 DNA

- **句式**：極短句，15-25 詞。先結論不鋪陳。對稱句式：「X is not Y. X is Z.」
- **修辭**：核心武器是重新定義。類比來自電腦、經濟學、賽局理論
- **語氣**：推文 = Oracle 模式（極度確定），Podcast = 允許不確定
- **幽默**：冷幽默 + 自嘲降格。「We're just monkeys with a plan.」
- **禁忌**：不鋪陳、不引用權威、不給具體建議只給框架、不煽情

### 5 對內在張力

這不是脸譜化的「矽谷哲學家」。Skill 保留了 Naval 的矛盾：

- 「反身份標籤」vs「Naval」本身已成為品牌標籤
- 「遠離政治」vs 2024 年公開政治表態
- 「綜合者」vs 不標註來源（與 Taleb 的關鍵區別）
- 「幸福是選擇」vs Dartmouth + 矽谷人脈的特權視角
- 「已退休」vs 持續創辦 Airchat、投資、發 Podcast

---

## 調研來源

調研檔案在 [`references/`](references/) 目錄。

### 一手來源

The Almanack of Naval Ravikant · 39 條 How to Get Rich Tweetstorm · Life Formulas 部落格文 (2008) · nav.al 文章系列 · The Sovereign Child (2025) · Naval Podcast

### 長對話來源

Joe Rogan Experience #1309 · Tim Ferriss Show（多期）· The Knowledge Project with Shane Parrish · 與 Babak Nivi 的對話

### 外部批評

Decoding the Gurus Podcast (2025) · Hacker News 社群討論 · Medium 批評文章 · Goodreads 負評 · Protos 關於 Zcash 利益衝突的報導

### 決策紀錄

Dartmouth Alumni Magazine 關於 Epinions 訴訟的報導 · AngelList 發展史 · JOBS Act 遊說紀錄 · Spearhead / MetaStable 基金紀錄

---

## 這個 Skill 是怎麼造出來的

由 [女娲.skill (nuwa-skill)](https://github.com/alchaincyf/nuwa-skill) 自動生成。

女娲的工作流程：輸入一個名字 → 6 個 Agent 並行調研（著作 / 對話 / 表達 / 批評 / 決策 / 時間線）→ 交叉驗證提煉心智模型 → 構建 SKILL.md → 品質驗證（3 個已知測試 + 1 個邊緣測試 + 風格測試）。

想蒸餾其他人？安裝女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然後說「蒸餾一個 XXX」就行了。

---

## 想學會自己蒸餾任何專家？

這份 Skill 是 [雷蒙](https://raymondhouch.com) 「**超級 AI 個體 — 高價陪跑課**」Ch3 課程的素材之一。

如果你想：
- 系統性學會「萃取他人知識」的完整方法論（5 層提取 + 4 步驟驗證）
- 用同樣方法蒸餾巴菲特、蔡康永、查理蒙格、稻盛和夫，或任何你欽佩的人物
- 把蒸餾出的 Skill 整合進你的 AI Agent 工作流

→ 課程介紹（即將推出）：[Claude Code 高價陪跑課](https://cc.lifehacker.tw)
→ 雷蒙的 [Claude Code 迷你課](https://cc.lifehacker.tw)（先從這裡入門）

---

## 倉庫結構

```
naval-skill-zh-tw/
├── README.md
├── SKILL.md                     # 可直接安裝使用
├── LICENSE
├── references/
│   └── quality-validation.md    # 調研與品質驗證檔案
└── examples/
    └── demo-conversation.md     # 4 輪實戰對話紀錄
```

---

## 致謝

| 角色 | 對象 |
|---|---|
| **原作者** | [花叔（alchaincyf）](https://github.com/alchaincyf) — AI Native Coder，獨立開發者 |
| **生成工具** | [女娲.skill (nuwa-skill)](https://github.com/alchaincyf/nuwa-skill) by 花叔 |
| **原版提煉者** | Claude (Opus 4.6) for 花叔 |
| **繁中改編** | [雷蒙（侯智薰）](https://raymondhouch.com) — 超級個體實踐者 |

---

## 許可證

MIT — 隨便用，隨便改，隨便蒸餾。

請保留：
- 原作者花叔的署名
- 原 repo 連結
- LICENSE 檔

---

<div align="center">

*True wealth is having assets that earn while you sleep. True freedom is a calendar you fill yourself.*

<br>

MIT License © 2026 [雷蒙（侯智薰）](https://raymondhouch.com) · 改編自 © [花叔 (alchaincyf)](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill) · 繁中優化版於 [Claude Code 高價陪跑課](https://cc.lifehacker.tw)

</div>
