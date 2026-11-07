# ⚓ ownHarbor (Powered by Human Attentions)

> **Let AI Teammates sail the 90% rough seas; save your `Human Attention` for the final 10% soul.**  
> 基于 `opencode serve` 构建的 Grok Bot 形态个人数字员工港湾 —— 零前端构建依赖、自带人类注意力审批闸门（Approval Gate）与动态可插拔画布。

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Engine](https://img.shields.io/badge/Backend-OpenCode_Serve-22c55e.svg)](https://github.com/sst/opencode)
[![UI](https://img.shields.io/badge/Frontend-Single_HTML_Zero_Build-38bdf8.svg)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#)

---

## 💡 为什么做 ownHarbor？

市面上 99% 的 Agent 面板都在重复造“传统聊天框”的轮子，或者陷入重度前端工程化的泥潭。而在真实的独立开发与一人公司业务中，我们需要的不是陪聊机器人，而是像 **xAI Grok Bot** 一样能异步干活、在关键节点挂起等待人类拍板的**数字员工编队（AI Teammates）**。

**`ownHarbor`** 遵循两大极简工程哲学：
1. **底层零魔改，交互全自由**：直接白嫖 `opencode serve` 强大的本地文件读写、终端执行与长上下文能力；前端浓缩为**单个 `index.html` 文件**，无需 Node 编译打包，3 分钟即可按个人直觉魔改出专属的业务交互画布。
2. **Human Attention Protocol（人类注意力协议）**：反对毫无灵魂的全自动 AI 垃圾矩阵。Bot 负责在后台完成选题排列组合、RAG 架构推演与初稿渲染（90% 苦力），随后自动挂起至 **Approval Inbox**，由人类花费 1 分钟注入真实情绪与工程判断（10% 灵魂），实现质感与效率的兼得。

---

## ✨ 核心特性与内置业务套件

仓库开箱即内置了完整的**「后端 CRUD 简历高并发升维 & 技术自媒体矩阵」**实战套件：

* 🤖 **Grok Bot 式数字员工编队（Teammates & Routines）**
  * **焦虑选题与初稿 Bot**：内置 `8×8×6×5` 四维正交选题发生器（人物处境 × 平庸 CRUD 模块 × 高并发解药 × 情绪切口），产出 1920 种不重样的技术叙事初稿，彻底告别 AI 车轱辘话。
  * **红绿对比首图渲染 Bot**：自动提取改写前后的核心反差，实时驱动右侧 600px 画布生成视觉冲击力拉满的对比图。
  * **评论区简历升维 Bot**：拒绝通用大模型“动辄百万 QPS”的假大空润色，严格对齐目标薪资职级，将平庸业务重构为无漏洞的工程演进方案。
* 🛡️ **人类注意力审批闸门（Human Attention Gate）**
  * 所有例行任务（Routines）产出均进入异步待审流，支持行内极速微调、一键打回重推或批准同步至工作台。
* 🎨 **动态可插拔画布（Pluggable Workspace Canvas）**
  * **视图 1：小红书/公众号 600px 红绿对比卡片实时渲染器**（所见即所得，支持一键导出）。
  * **视图 2：后端项目 STAR 升维 + 面试官夺命 5 连问对照工作台**（防止简历写得太牛、面试一问三不知）。

---

## 📚 内置六大后端高并发拔高知识库（RAG Playbooks）

为了彻底消除大模型的工程幻觉，`ownHarbor` 在 `/playbooks` 目录下持续维护基于真实大厂生产环境的六大升维映射库：

1. **慢查询与海量数据治理**：深分页 `Deferred Join` 优化、联合索引失效排查、冷热数据归档与异构同步 ES。
2. **高并发读与多级缓存体系**：`Caffeine + Redis` 多级缓存防击穿、延迟双删与 `Canal` 监听 Binlog 最终一致性。
3. **高并发写与异步解耦**：`RocketMQ / Kafka` 削峰填谷、消息丢失对账与自定义幂等表设计。
4. **分布式协调与事务**：`Redisson` 分布式锁 WatchDog 实战、状态机消除千行 `if-else` 分支。
5. **JVM 与线上故障排查故事库**：百万级 Excel 导出引发 `Full GC / OOM` 排查、死锁与 CPU 100% 完整证据链模板。
6. **防穿帮夺命追问底稿**：每个技术组件配套 5-10 道面试官底层追问与边界异常标准回答。

---

## 🚀 30 秒极速启动（Quick Start）

### 方式一：零配置直接体验（内置 Mock 演示模式）
无需安装任何后端环境，直接克隆仓库并在浏览器双击打开 `index.html`，即可体验完整的四维选题生成、审批流转与简历红绿对比卡实时渲染：
```bash
git clone [https://github.com/](https://github.com/)<your-username>/ownHarbor.git
cd ownHarbor
open index.html  # Windows 用户直接双击 index.html