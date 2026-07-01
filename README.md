# 以色列檔案 · An Israel Archive

> 一座持續生長的**中文深度檔案庫**,收藏那些形塑了以色列的人、事與思想。
> 每一篇都是一個關於信念與重生的故事——從復興一門語言,到重生一個民族的靈魂。

採「天下雜誌風」的長文排版:溫潤的紙感底色、藍金配色、中文襯線字 + 希伯來文字體,適合靜下心閱讀。

---

## 🔗 線上瀏覽

部署在 GitHub Pages:

**[https://rubyboss2004.github.io/israel-archive/]**

> ⚠️ 上面的網址是範例。實際部署後,把「你的帳號」和 repo 名稱換成你自己的即可。

---

## 📚 目前收錄的文章

| 分類 | 文章 | 人物 | 主題 |
|------|------|------|------|
| 人物 | [希伯來語之父](ben-yehuda.html) | 以利澤・本-耶胡達 (Eliezer Ben-Yehuda, 1858–1922) | 復興希伯來語 |
| 人物 | [勞動的先知](ad-gordon.html) | 亞倫・大衛・戈登 (Aaron David Gordon, 1856–1922) | 勞動宗教 / 勞動錫安主義 |

---

## 🗂️ 檔案結構

```
以色列檔案/
├── index.html            ← 首頁(卡片牆),打開網址會先看到這個
├── ben-yehuda.html       ← 文章:希伯來語之父
├── ad-gordon.html        ← 文章:勞動的先知
├── *.template.html       ← 各文章的工作備份(換圖用,不影響網站)
├── images/               ← 原始圖檔(備份用;網頁的圖已內嵌,部署時可不上傳)
└── README.md             ← 本說明檔
```

**重點:** 每個 `.html` 都是**自成一體的單一檔案**——圖片以 base64 直接內嵌在檔案裡。所以每篇文章:
- 沒有網路也能開
- 可以單獨 email 給別人,對方一樣看得到圖
- 部署時只需要三個 html(`index`、`ben-yehuda`、`ad-gordon`),`images/` 資料夾非必要

---

## 💻 在自己電腦上看

直接用瀏覽器打開 `index.html`(雙擊即可),不需要任何伺服器或安裝。

---

## 🚀 部署到 GitHub Pages(全程網頁操作,不用打指令)

1. 到 [github.com](https://github.com) → 右上角 `+` → **New repository** → 取英文名(例如 `israel-archive`)→ 選 **Public** → Create。
2. 進 repo → **Add file** → **Upload files** → 把 `index.html`、`ben-yehuda.html`、`ad-gordon.html` 三個檔拖進去 → **Commit changes**。
3. **Settings** → 左側 **Pages** → Source 選 **Deploy from a branch** → 分支 **main**、資料夾 **/(root)** → **Save**。
4. 等 1–2 分鐘,同頁會出現你的網址,打開就是首頁。

---

## ➕ 新增一篇文章

1. **查資料**:用 `israel-research` skill 把新主題整理成大綱(繁中不簡化、原文對照、附出處)。
2. **做網頁**:用 `israel-site-builder` skill 套進同一套風格,產出新的 `xxx.html`(圖用 Wikimedia 公有領域圖,再內嵌成 base64)。
3. **上首頁**:在 `index.html` 的「人物」卡片區,複製一張卡、換成新文章的圖與資訊、連結指向新檔。
4. **上傳**:到 GitHub repo 再 Upload 新的 html + 更新後的 `index.html`,Commit 後網站幾分鐘自動更新。

> 這兩個 skill 存在 `~/.claude/skills/`,由 Claude Code 使用。

---

## 🖼️ 圖片與資料來源

- **圖片**:全部取自 [Wikimedia Commons](https://commons.wikimedia.org),以公有領域(Public Domain)歷史影像為主;少數為 CC BY-SA 授權者已於各文章頁尾標註攝影者。
- **文字資料**:交叉比對多個來源整理,包括 English Wikipedia、My Jewish Learning、Encyclopædia Britannica、Jewish Virtual Library、Encyclopedia.com、Brandeis University 等;各文章頁尾附有主要來源清單。

---

## ✍️ 製作

由 **ruby** 整理編纂,內容以中文深度長文呈現,面向對以色列歷史、文化與思想有興趣的中文讀者。

---

*這座檔案庫還在生長中。*
