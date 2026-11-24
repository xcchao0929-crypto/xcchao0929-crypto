<!--
  个人主页 README。只有在本仓库同时满足下列条件时 GitHub 才会渲染：
  1) 仓库名为 xcchao0929-crypto（与用户名完全一致）
  2) 仓库为 public
  3) 根目录存在 README.md
  维护方式：直接改文件 → python3 tools/gh_sync.py ...（见 workspace 说明）
-->

### 每天一份 AI 插件 / Skill 观察

<!-- LATEST:START -->
> **最新一期 · 2026-11-24（10:02）**
> Top 1 `mattpocock/skills` **331,431 ★**（+889）· Top10 合计 **4,905**（**+19.9%**，一周最大反弹）· **预测 4/5**
> 🔥 头条是 `elementalsouls/Claude-BugHunter`：**+1,942（+10.84%）三日连爆**（1,803 → 1,688 → 1,942），今天一天四个 `feat` 提交（证据链固化 / 默认数据隔离 / 利用补全）——热度与开发量同时上升，不再只是曝光 · 🆕 小仓库爆发 `mjmirza/app-store-compliance` **+986（+24.49%）**：124 条 App 商店驳回模式 + 欧盟 AI 法案截止日期，带 agent skill · ❌ 唯一落空：我给 BugHunter 的区间上限（1,200）比它前两天的实际值都低 → 新规矩「连续 N 天高增，第 N+1 天下界不低于前 N 天最小值」· ⚠️ 运维：脚本编辑 bug 致首跑漏 8 个仓库，已修 + 加验收步骤 · 连续二十七日无断档
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
