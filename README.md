# 中国足球发展助手

面向球迷、球员、教练、青训机构和俱乐部的公开 Skill。它用官方资料核对赛程和政策，再把比赛观察转成训练、试点和复盘计划。2030 年世界杯是规划目标，赛程与资格规则以赛事方的正式文件为准。

## 阅读和下载

| 文件 | 用途 |
| --- | --- |
| [UTF-8 纯文本](docs/china-football-development.txt) | 完整说明、指标、示例和公开来源，优先提供给国内大模型读取或上传分析。 |
| [现代 Word](docs/china-football-development.docx) | 可编辑的完整指南。 |
| [旧版 Word](docs/china-football-development.doc) | Word 97–2003 格式，内容与 DOCX 相同。 |
| [旧版 PowerPoint](docs/china-football-development.ppt) | PowerPoint 97–2003 格式，适合展示与讲解。 |
| [Skill 入口](china-football-development/SKILL.md) | 支持 Skill 的平台可导入整个 `china-football-development` 目录。 |
| [球员和教练工作簿](china-football-development/assets/player-coach-workbook.xlsx) | 球员跟踪、教练现场观察和教练改进计划。 |

Gitee 提供免登录的 [TXT 浏览页](https://gitee.com/xxxxzhu/china-football-development/blob/main/docs/china-football-development.txt) 和 [TXT 下载链接](https://gitee.com/xxxxzhu/china-football-development/raw/main/docs/china-football-development.txt)。也可打开 [GitHub TXT 浏览页](https://github.com/yingzao-studio/china-football-development/blob/main/docs/china-football-development.txt) 或 [下载 GitHub TXT 原文](https://raw.githubusercontent.com/yingzao-studio/china-football-development/main/docs/china-football-development.txt)。

## 国内大模型实测和用法

| 平台 | 实测结果 | 使用方法 |
| --- | --- | --- |
| DeepSeek | 开启智能搜索后，GitHub 和 Gitee 的 TXT 浏览页均读取成功，三问全对。两站的原始下载链接均读取失败。 | 开启「智能搜索」，把上面任一 TXT 浏览页的链接和问题一起发给 DeepSeek。 |
| 豆包 | 专家模式读取 GitHub 的 TXT 浏览页或 Gitee 的 TXT 原始下载链接，三问全对。快速模式测试 GitHub 的 TXT 浏览页，两次均未答题，复测明确回复读取失败。Gitee 的原始下载链接在快速模式下读取失败，Gitee 的浏览页在两种模式下均未答题。此前用 GitHub 的 TXT 原文链接也曾答对三问。 | 在新对话中切换为「专家」，把上面的 GitHub TXT 浏览页或 Gitee TXT 下载链接和问题一起发送。也可以使用 GitHub 的 TXT 原文链接。 |
| 通义千问（阿里云百炼 Qwen3.8-Max） | 开启搜索后，GitHub 和 Gitee 的 TXT 浏览页及原始下载链接均读取失败，三问未作答。把 TXT 作为附件上传后，关闭搜索也能答对三问。 | 从上面的 Gitee TXT 下载链接保存 `china-football-development.txt`。在百炼体验中心打开「文本模型」，选 Qwen3.8-Max，点「+」→「文件&文档」，上传 TXT。等解析完成，再发送问题。 |

实测使用了同一道预算题。请模型只依据 TXT 引用「示例直接支出上限」开头的短句并给出金额，列出裁判与办赛和导师各自的预算，再用一句话分析应优先压缩哪项开支及其依据。通过测试的答案均给出预算上限 18,000 元、裁判与办赛 4,000 元、导师 3,000 元，并依据原文建议先减少跨区交通开支。

试用问题：用官方赛程给我做一份国足观赛清单，或者用工作簿设计一支球队的 90 天受压出球试点。

## 许可

本仓库原创 Skill 指南、模板和示例采用 [MIT 许可证](LICENSE)。第三方网站、赛事资料及标识由各自权利方管理。仓库引用其公开链接。项目为独立工具。
