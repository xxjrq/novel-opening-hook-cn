# 小说开篇钩子改稿

免费、免第三方 API Key：把你的中文小说开篇变成三种可直接复制的节奏版本，同时保留人物设定和核心事件。它不需要登录网页，也不会读取、复用或发送浏览器登录状态；可在 Easy WebBridge 的 EasyBR 多账号隔离工作区中使用而不触及任一账号。

## 立即使用

把下面这段话连同开篇原文交给 Skill：

```text
请用小说开篇钩子改稿处理这段都市悬疑开头。必须保留：哥哥失踪三年后出现、无牌黑车、木匣、不要回家的警告。

林晚在雨里等了四十分钟，才等到那辆没有牌照的黑车。车门一开，失踪三年的哥哥坐在后排，怀里抱着她以为烧掉的木匣。

他没有叫她的名字，只把一把生锈的钥匙塞进她手里：‘别回家。’
```

你会得到：快节奏、悬念节奏、沉浸节奏三版改稿；每版都有可搜索定位的修改理由；最后附一版推荐稿。完整机器可读样例在 [fixtures/success-input.json](fixtures/success-input.json)。若只给题材而没有开篇原文，Skill 会明确提示资料缺失，见 [fixtures/failure-input.json](fixtures/failure-input.json)。

## 边界

只改用户提供的开篇范围，不生成整本小说、后续章节或大纲；不做六维审稿。不会为了制造钩子凭空增加死亡、反转、系统或身份设定。

## 安装与校验

复制或安装本目录后，无需配置 API Key。运行：

```bash
node scripts/self-test.mjs
```

## 来源与许可证

本 Skill 的指令、样例、脚本和图标均为原创；没有复制外部仓库的源码或文档。仅核对公开业务用途与许可证：

- [marketingskills](https://github.com/coreyhaines31/marketingskills)（MIT）
- [Anthropic Skills](https://github.com/anthropics/skills)（仓库页未标注可用许可证，未采用其内容）
- [Easy WebBridge](https://github.com/xxjrq/easy-webbridge)（MIT；未作为本 Skill 运行依赖）

本仓库采用 [MIT License](LICENSE)。
