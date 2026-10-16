# Morimens Translation Editor / 忘却前夜 翻译编辑器

**[English](#english) | [中文](#中文)**
## English

> Dear Keeper, thank you so much for your support.
> This translation editor was developed in-house by B.I.A.V. Studio for our internal translators. It is now open to every volunteer who would like to help translate *Morimens*.
> The ever-hospitable Mr. Doresain will introduce its features and accompany you through each translation.

### What it does

- **Source on the left, translation on the right**: Chinese source text in one column, your translation in the next, row by row.
- **Highlighting**: rich-text tags (e.g. `<Title:...>`), placeholders and numbers are highlighted in light blue, and glossary terms in light green, so nothing gets missed.
- **Autocomplete**: type `<`, `[` or `{` to get tags that appear in the source; type the first letters of a term to get its official translation; numbers are suggested too.
- **Glossary hints**: terms found in the source are listed with their type. Click a term to insert it at your cursor.
  - Think a term's translation is wrong? Double-click it to edit; edited terms can be exported for our review.
  - Select text in the source and right-click to define a new term.
- **Similar translations**: when a source line closely matches something translated before, past translations are suggested. Click "Compare" to see the differences below the source (yellow = only in the text you are translating, blue = only in the past source text).
- **Rich-text check**: verifies that tags are closed correctly, flags stray spaces, and catches missing placeholders.
- **Productivity**: paste a whole column, jump to any page, filter by key / source sheet / source text, group similar sources together, and automatically reuse translations you have confirmed for identical sources.
- **Save any time**: click "Save progress" or press `Ctrl+S`. Progress accumulates in the same CSV and is never overwritten. If you close the program with unsaved changes, Mr. Doresain will remind you.
- **Comments**: leave a comment or question on any row; it is exported along with your translation.

### Download and install

1. Open **Releases** on the right of this page and download the latest `MorimensTranslationEditor-v1.zip`.
2. Unzip it anywhere (**no installation needed**).
3. Double-click `MorimensTranslationEditor.exe`.

Requires Windows 10 / 11 (64-bit). On first launch Windows may show an "unknown publisher" warning; click "More info" and then "Run anyway". The program does not upload your work anywhere; everything stays on your computer.

### How to use

1. **Import a file**: prepare a CSV or xlsx with at least a "Key" column and a Chinese source column.
2. **Confirm columns**: the program asks you to confirm what each column means and to pick the **target language**.
3. **Translate**: type in the right-hand box. Click "Confirm" when a line is done; only confirmed lines count towards reuse and suggestions.
4. **Save**: click "Save progress". The result appears in the `out/` folder next to the program. Send the exported CSV back to us.

A short illustrated guide appears on first launch, and you can reopen it at any time from the main screen.

### About data

- The official glossary and rich-text format tables are built in. **You do not need to choose a development branch** (the option is greyed out for volunteers).
- Terms you define, translations you change and new translations you write are stored in `out/userdata/` and reused next time.
- "Similar translations" needs past translation tables (the `panorama/` folder). If you want this feature, contact us for the file of your language and drop it into `panorama/` next to the program. Everything else works without it.

### Feedback

Found a bug or have a suggestion? Please open an **Issue** in this repository, or contact us: (add your contact info here)

May the Silver Key guide our path, and may we soon conquer the sky-piercing Tower of Babel.
---

## 中文

> 亲爱的守密人，感谢您的热情相助。
> 这是 B.I.A.V. Studio 自主开发的翻译编辑器，原供内部译者使用，如今开放给每一位愿意参与《忘却前夜》（Morimens）翻译的志愿者。
> 好客的杜勒赛因先生会为您介绍这件小工具，并陪伴您完成每一次翻译。

### 它能帮你做什么

- **一列原文、一列译文**：左边是中文原文，右边是你的译文，逐行填写，一目了然。
- **标签与数字高亮**：原文和译文里的富文本标签（如 `<Title:活动规则>`）、占位符和阿拉伯数字用浅蓝色标出，术语用浅绿色标出，不容易漏改。
- **输入联想**：在译文里输入 `<`、`[`、`{` 会自动联想原文里出现过的标签；输入术语的前几个字母会联想官方术语译法；数字也会联想。
- **术语提示**：自动找出原文命中的术语和类型，点一下术语就能插入到光标处。
  - 觉得术语译法有问题？双击术语即可编辑，编辑后可导出供我们参考。
  - 在原文里选中文字，右键即可新定义一条术语。
- **相似译文推荐**：遇到和以前译过的文本高度相似的原文时，会推荐历史译文。点「对比」可以在原文下方看到两段原文的差异（黄色是你正在翻的原文独有的部分，蓝色是历史原文独有的部分）。
- **富文本检查**：检查标签是否正确闭合、是否多余空格、占位符是否缺失。
- **批量效率**：整列粘贴、翻页和跳页、按 Key / 表来源 / 原文内容筛选、相似原文排在一起、相同原文自动复用你已确认的译文。
- **随时保存**：点「保存进度」或按 `Ctrl+S`，进度会累计写入同一个 CSV，不会覆盖丢失。关闭程序时如果还有未保存内容，杜勒赛因会提醒你。
- **留言**：每一行都能写 comment（疑问或备注），会随译文一起导出。

### 下载与安装

1. 打开本页右侧的 **Releases**，下载最新的 `MorimensTranslationEditor-v1.zip`。
2. 解压到任意位置（**不需要安装**）。
3. 双击 `MorimensTranslationEditor.exe` 即可。

需要 Windows 10 / 11（64 位）。第一次运行时 Windows 可能提示"未知发布者"，点「更多信息」→「仍要运行」即可；程序没有联网上传你的内容，所有数据都保存在本机。

### 使用步骤

1. **导入文件**：准备一份 CSV 或 xlsx，至少包含「Key」和「中文原文」两列。
2. **确认列含义**：程序会让你确认每一列的用途，并选择你要翻译的**语种**。
3. **开始翻译**：在右侧译文框中填写，写完一行点「确认」，它才会算作你的定稿并参与后续的复用与推荐。
4. **保存**：点「保存进度」，结果会出现在程序文件夹的 `out/` 里。把导出的 CSV 发回给我们即可。

首次打开会有简短的图文引导，之后可以随时点界面上的按钮重新查看。

### 关于数据

- 程序已内置官方术语表和富文本格式表，**无需选择开发分支**（该选项对志愿者置灰）。
- 你新定义的术语、修改过的译法和新产生的译文，会存档在程序目录的 `out/userdata/`，下次启动自动沿用。
- 「相似译文推荐」需要历史译文表（`panorama/` 文件夹）。如果你需要这项功能，请联系我们获取对应语种的文件，放进程序文件夹下的 `panorama/` 即可。没有它，其他功能不受影响。

### 反馈与交流

遇到问题或有建议，欢迎在本仓库提 **Issue**，或联系：（在此填写你们的联系方式）

愿银钥指引前路。愿我们早日征服那座通天的巴别塔。



May the Silver Key guide our path, and may we soon conquer the sky-piercing Tower of Babel.
