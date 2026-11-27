<!--
  个人主页 README。只有在本仓库同时满足下列条件时 GitHub 才会渲染：
  1) 仓库名为 xcchao0929-crypto（与用户名完全一致）
  2) 仓库为 public
  3) 根目录存在 README.md
  维护方式：直接改文件 → python3 tools/gh_sync.py ...（见 workspace 说明）
-->

### 每天一份 AI 插件 / Skill 观察

<!-- LATEST:START -->
> **最新一期 · 2026-11-27（10:00）**
> Top 1 `mattpocock/skills` **333,633 ★**（+704）· Top10 合计 **4,705**（**+2.3%**）· 🎯 **预测 5/6**
> 🏅 **`archify` 破 10 万**（100,598 ★，Apache-2.0）——架构图 skill，它的文档里已经写 DSH 版本说明；10 万俱乐部共 **17 家** · 🔥 `Claude-BugHunter` **+1,584 第四日连爆**，但今天机制换了：不是发功能，是**上 PyPI**（`ci(release): add PyPI Trusted-Publishing workflow`），安装门槛从 git clone 降到 `pip install` · 🔥 `app-store-compliance` 发 **v2.5.3** + `--tool kiro` 接入，+549（**+8.43%**），连续第四日高增 · ❌ 唯一落空：`obsidian-skills` 给 40~150 实际 **+266**——我把它当「平台期线性衰减」，漏了它**一夜连开 4 个新 host 安装入口**（Kiro / Muse / Antigravity / Hermes Marketplace）→ **发版 ≠ 唯一脉冲，铺分发入口比改功能更能拉星数**，已写进 METHOD · 🟢 `ffmpeg-skill` 一晚连发 v4.15.0 / v4.16.0，「发版驱动」在它身上恢复 · 🆕 `heygen-com/hyperframes` 90,902 ★（+707，HTML→MP4 成片层）· 连续三十日无断档
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
