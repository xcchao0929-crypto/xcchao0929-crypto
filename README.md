<!--
  个人主页 README。只有在本仓库同时满足下列条件时 GitHub 才会渲染：
  1) 仓库名为 xcchao0929-crypto（与用户名完全一致）
  2) 仓库为 public
  3) 根目录存在 README.md
  维护方式：直接改文件 → python3 tools/gh_sync.py ...（见 workspace 说明）
-->

### 每天一份 AI 插件 / Skill 观察

<!-- LATEST:START -->
> **最新一期 · 2026-11-28（10:00）**
> Top 1 `mattpocock/skills` **334,290 ★**（+657）· Top10 合计 **4,795**（**+1.9%**）· 🎯 **预测 6/7**
> 🏅 **`ponytail` 破 20 万**（200,157 ★）——20 万俱乐部 6 家；**一个月没发版、最后一次提交 11-22，照样 +766**。它的定位是「让 agent 像最懒的资深工程师思考」，和榜单主流方向相反：星数是认同度，不是使用量 · 🔥 `app-store-compliance` **+890（+12.61%）加速**，五日曲线 986 / 885 / 612 / 549 / 890 不是单调递减 → **四天样本不足以判趋势** · ❌ 同一对象连错两次：`obsidian-skills` 昨天给 40~150 实际 +266，今天改口 60~200 又给高到 **+308**。第一次错在没看到渠道扩张，第二次错在把「多日过程」当「单日脉冲」——**渠道扩张是多日尾巴，第 2~4 天仍在放量是常态**，已写进 METHOD · 🟢 `ffmpeg-skill` 一晚又两版（v4.22.1 / v4.22.2），一天跨 7 个 minor，是全榜唯一「发版频率与增量严格同步」的对象 · 🔍 线索：**Kiro 两天内被 `obsidian-skills` 与 `app-store-compliance` 两个不同赛道的热门 skill 适配**，疑其在做生态招募 · 连续三十一日无断档
<!-- LATEST:END -->

---

## 📬 GitHub 最火 AI 插件 / Skill 日报

每天北京时间 **10:00** 自动跑一次：抓 GitHub 上最火的 Agent Skill / 插件，附安装命令与可用性判断，然后归档成一篇带日期的 markdown。

- **口径**：仓库总 star 数（非期间增量），每期标注抓取时间戳
- **范围**：以 skill / 插件为主题的仓库；纯 awesome 清单另列
- **判断**：区分 `已验证`（安装命令取自 README）与 `待核实`（未实测或依赖第三方额度）

> 仓库目前为 **private**：日报会持续积累，内容稳定后考虑公开。

---

## 🧭 关注方向

| 方向 | 说明 |
|---|---|
| Agent Skills | 可组合的 SKILL.md 技能包、插件市场、harness 兼容性 |
| 内容与投放 | 营销类 skill、去 AI 味写作、短视频选题研究 |
| 知识管理 | Obsidian / 结构化笔记 / 增量归档工作流 |

---

## 🛠 本地起一套

```bash
# 只要榜单，不用装任何东西：每天 10:00 来看这个主页的「最新一期」
# 想自己复现一期：
curl -s "https://api.github.com/search/repositories?q=agent+skills+in:name,description&sort=stars&order=desc&per_page=15"
```

---

<sub>自动更新 · 数据源 GitHub Search API</sub>
