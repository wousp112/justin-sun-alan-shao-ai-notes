# 孙宇晨 × 邵艾伦：AI 时代怎么抓机会

[English](README.en.md)

孙宇晨和邵艾伦聊了 4 小时 22 分钟，我们从里面挑出 15 个观点，每个都配了一篇教程，写清楚怎么一步步做，用什么工具。

原视频：[YouTube](https://www.youtube.com/watch?v=0Z-vhBvBmUY) · 主持人：[邵艾伦 @AlanShao111](https://x.com/AlanShao111)

## 从哪看起

| 你想 | 看这个 |
| --- | --- |
| 自己动手试 | 先看 [00](guides/00-准备.md) 装好 AI，再挑一篇感兴趣的 |
| 让 AI 替你出主意 | 把 [AGENT.md](AGENT.md) 复制给你的 AI，再说说你的情况 |
| 只看重点 | [精华.md](精华.md) |
| 看原话 | [全文.md](全文.md)，整场逐字稿，带时间戳 |

## 15 个观点

点观点名进到教程。「推荐」是我们觉得最好用的工具，「国内」是不用海外手机号和信用卡就能开的替代品。

| | 观点 | 从哪下手 | 推荐 | 国内 |
| --- | --- | --- | --- | --- |
| 01 | [把生活 AI 化](guides/01-生活AI化.md) | 建一个文件夹，让 AI 每天替你写日报 | Claude Code / Codex、Obsidian、Oura | Kimi Code、思源笔记、Zepp |
| 02 | [没钱也能开始](guides/02-没钱也能开始.md) | 挑一件经常重复的事，用免费额度交给 AI | Gemini CLI（有免费额度） | Kimi Code、Qwen Code |
| 03 | [先升级操作系统](guides/03-升级操作系统.md) | 写下一个看法，找资料来验证它 | Obsidian、NotebookLM | 思源笔记、Kimi |
| 04 | [百分之百相信 AI](guides/04-百分之百相信AI.md) | 同一个问题问三个模型，挑最好的去做 | ChatHub、Arena | Kimi、通义、智谱各问一遍 |
| 05 | [商机全球找](guides/05-商机全球找.md) | 去海外论坛看看你这行的人在抱怨什么 | Google Trends、Shopify、Wise | 店匠、空中云汇、万里汇 |
| 06 | [先探路，再下注](guides/06-先探路再下注.md) | 多找几个候选，挑出最好的先试一下 | Perplexity、Airtable | 秘塔搜索、飞书多维表格 |
| 07 | [身体是本钱](guides/07-身体是本钱.md) | 把手环数据交给 AI，让它盯着趋势 | Oura / WHOOP、Apple 健康 | Zepp / 华为、Keep |
| 08 | [逐水草而居](guides/08-逐水草而居.md) | 搞清楚你要的机会大多在哪个城市 | Nomads.com、Levels.fyi | 脉脉、电鸭社区 |
| 09 | [机器读得懂才值钱](guides/09-机器读得懂.md) | 把常用资料转成 AI 能读的 Markdown | MarkItDown、OCRmyPDF | MinerU |
| 10 | [内容和投资不用二选一](guides/10-内容和投资.md) | 内容和投资分两个文件夹，各记各的 | Ghost / beehiiv、Portfolio Performance | 公众号、本地记账 |
| 11 | [Small ego](guides/11-small-ego.md) | 让 AI 站在反对者那边反驳你 | Decision Journal 方法 | 同左，任何笔记工具 |
| 12 | [先自由，后财富](guides/12-先自由后财富.md) | 翻一遍账单，算出你的缓冲金 | YNAB / Actual Budget | 钱迹、随手记 |
| 13 | [游戏版本会更新](guides/13-游戏版本更新.md) | 订阅几个一手信息源，让 AI 帮你看变化 | Folo、GitHub Trending、Awesome 列表 | Folo |
| 14 | [缺啥补啥](guides/14-缺啥补啥.md) | 给自己出一道目标岗位的模拟题 | Forage、ADPList | 牛客、即刻 / 脉脉找人聊 |
| 15 | [多创造，少消费](guides/15-多创造少消费.md) | 把刚搞懂的东西写成教程发出去 | GitHub Pages、Quartz | 公众号、B 站 |

每篇教程开头是孙宇晨的原话和视频时间点，想看他当时怎么说，可以直接跳过去。后面是一步步的做法，按先后顺序排，每一步花多久看你自己。最后一段是写给 AI 的话，整段复制给你的 Agent，它会照着帮你装软件、建文件夹。

## 全文是怎么做出来的

原视频 4 小时 22 分 29 秒，YouTube 上没有字幕。

我们把音轨切成 57 段，每段 5 分钟，相邻两段重叠 20 秒，防止句子在切口处被截断。每段交给 Gemini 3.8 Flash 转录。Gemini 系列在 [Artificial Analysis 语音转文字榜单](https://artificialanalysis.ai/speech-to-text)上排在前十，同系列的 Gemini 3.5 Transcribe 词错误率是 2.6%。

第一轮有 5 段没有通过格式检查，我们把它们切成 30 个更短的片段重新转。有一段出现了一长串重复文字，也单独重转了一遍。

转完以后，我们从开头、中间、结尾各截 30 秒音频，单独再识别一次，拿去和主稿对照，内容和顺序都对得上。

最后得到约 12 万字，1,743 条发言，每条都标了时间，拿着时间就能在视频里找到原话。说话人按每段的发言量区分成孙宇晨和邵艾伦。

还有几处要留意。全文没有逐句人工听校，个别人名和同音词可能有误，引用原话前最好回看视频。相邻两段重叠的地方，开头可能有几句重复，文中都标了出来。00:32:40 那段两个人的话被识别成了一整段，没能分开。

## 授权

精华、教程和 AGENT.md 随便用，注明出处就行。访谈内容版权归原作者。详见 [LICENSE](LICENSE)。
