<div align="center">
  <img src="nexusos-icon.svg" alt="NexusOS Logo" width="130" />
  <h1>NexusOS</h1>
  <p><strong>专为学者打造的终极 AI 原生个人科研与学习操作系统</strong></p>

  <p>
    <a href="https://github.com/Tomoyo-Kusosawa/Nexus/releases"><img src="https://img.shields.io/badge/版本-v1.0.2-cyan.svg?style=flat-square" alt="Version"></a>
    <a href="https://github.com/vuejs/core"><img src="https://img.shields.io/badge/Vue.js-3.x-4FC08D.svg?style=flat-square&logo=vue.js" alt="Vue"></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5.x-3178C6.svg?style=flat-square&logo=typescript" alt="TypeScript"></a>
    <a href="https://www.nexusos.top"><img src="https://img.shields.io/badge/官网-nexusos.top-blue.svg?style=flat-square" alt="Website"></a>
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/协议-MIT-green.svg?style=flat-square" alt="License"></a>
  </p>

  <p>
    <a href="./README.md">English</a> | <b>简体中文</b> | <a href="./README_zh-TW.md">繁體中文</a>
  </p>
</div>

---

## 📖 项目简介

**NexusOS** 是一款专为学者、硕博研究生、科研人员及算法工程师打造的**本地优先、AI 原生的一体化学术科研学习操作系统**。它打破了传统科研过程中工具割裂的壁垒，将文献流转、智能研读、LaTeX 论文工坊、实验资产管理、拓扑图谱以及组会周报整合到一个高度安全、极度流畅的单一应用中。

---

## ✨ 核心特性深度解析

### 🤖 1. 全局 AI 智能管家与工作台中枢
* **双管线执行引擎：**
  * **标准执行管线：** 能够将自然语言指令精准解析为底层系统动作（JSON Actions），一键批量调度文献状态、日程及任务。
  * **Super 学术创作管线：** 融合深度长文推理、沙箱代码运行与论文直接写入功能。
* **多维 RAG 检索与风格克隆：** 支持挂载多篇文献，既可切片提取事实知识，亦可 1:1 克隆高水平标杆文献的学术句式、行文逻辑与段落厚度。
* **动态技能插件市场：** 支持一键从 GitHub 仓库拉取专业学术技能包，无缝拓展专属科研工作流。
* **AI 算力监控台：** 实时监听全局 Token 吞吐消耗，监控 Ollama、OpenAI、DeepSeek 等各大节点的连通健康度。

### 📚 2. 文献流转管线 (Kanban Pipeline)
* **全流程看板管理：** 在“待读”、“略读”、“精读”与“复现中”四大队列间自由拖拽，精准把控阅读进度。
* **智能解析与智能防重：** 拖拽 PDF 秒级解析标题、作者、DOI、期刊及年份，自动检测库内重复文献，避免重复阅读。
* **内置镜像源文献捕获：** 支持配置 SciDown 等镜像路由，输入 DOI 即可通过内嵌环境高速抓取文献。
* **归档冷库与 BibTeX 导出：** 拖拽至底部即可将已读文献送入归档库，支持一键复制标准学术 BibTeX 引用代码。

### 📖 3. 全能沉浸式 AI PDF 阅读器
* **双栏全文对照翻译：** 支持 PDF 原文与 AI 翻译后的高质量 Markdown 排版双栏并列呈现，带有平滑同步滚动机制。
* **多维深度批注：** 划词高亮/下划线、自由拖拽的多色便签，并支持按 `想法`、`疑问`、`重点`、`待办` 分类标记。
* **伴读 AI Copilot：** 针对当前文献即时提问、一键生成含核心论点/方法论的结构化总结，并由 AI 推荐高相关度拓展文献。
* **长笔记创作室：** 内置完整 Markdown 笔记系统，自动关联至全局资源图谱，支持一键导出为 `.md` 或排版 `.pdf`。

### ✍️ 4. 论文工坊 (Paper Studio)
* **混合编辑革命：** 采用 Tiptap + KaTeX 架构，兼具富文本排版的丝滑与原生 LaTeX 代码块的严谨，繁杂公式双击即改。
* **顶刊模板生态：** 原生集成 **IEEE Transactions**（单/双栏）、**ACM Conferences** (`acmart`)、**Nature/Springer**、**Elsevier** (`elsarticle`)，支持直接上传官方 `.zip` 模板包。
* **Overleaf 级本地极速编译：** 无缝对接本地 TeXLive 环境（支持 `xelatex`、`pdflatex`），具备输入防抖自动编译、实时 PDF 渲染与精准日志报错定位。
* **智能交叉引用系统：** 自动索引全文插图 (`\ref{fig:...}`)、公式 (`\ref{eq:...}`) 与文献 (`\cite{...}`)。
* **AI 论文审稿专员：** 自动生成三线表（Booktabs）、深度润色学术语气、精简降重，甚至生成万字盲审评估意见报告。

### 🕸️ 5. 学术资产、实验管理与资源图谱
* **动态资源图谱 (Resource Graph)：** 自动将文献、工业数据集、个人笔记、代码环境编织成交互式拓扑网络，支持微观关系漫游。
* **工业数据集与浏览器书签扫描：** 统一管理本地盘符映射与线上数据源，一键扫描 Chrome、Edge 等浏览器收藏夹提取科研数据集。
* **代码环境与 IDE 联动：** 记录 Conda 环境与执行命令，一键调用系统底层唤醒 VS Code 对应工作区。
* **智能组会周报引擎：** 自动遍历您一周内的真实科研行为轨迹（完成任务、精读文献、工坊修改），一键生成详尽周报并支持 AI 润色。

### 🧩 6. 自定义动态工作区
* **模块化自由排版：** 任意组装无尽纵向日历、番茄专注钟、科研贡献热力图、截稿雷达等内置组件。
* **沙箱自定义挂件开发：** 支持编写 HTML/JS/CSS 代码并在独立沙箱中运行，通过 `PHM.api` 自由读取系统底层数据。

---

## 🛠️ 技术架构

* **前端框架：** Vue 3 (Composition API), TypeScript, Vite
* **编辑器内核：** Tiptap, ProseMirror, KaTeX
* **PDF 解析引擎：** PDF.js
* **样式与图标：** TailwindCSS, Lucide Icons
* **数据存储：** 本地 SQLite 数据库（本地优先，绝不上报隐私数据）

---

## 🚀 快速上手

### 环境准备
- Node.js (`>= 18.x`)
- Git
- 本地 TeXLive / MacTeX 环境（可选，若需本地编译 LaTeX 生成 PDF）

### 本地部署运行

```bash
# 1. 克隆代码仓库
git clone https://github.com/Tomoyo-Kusosawa/Nexus.git

# 2. 进入项目目录
cd Nexus

# 3. 安装依赖包
npm install

# 4. 启动本地开发服务
npm run dev
```

## 🔗 官方网站与技术支持

* 🌐 **官方网站：** [www.nexusos.top](https://www.nexusos.top)
* ✉️ **技术支持与建议反馈：** [support@nexusos.top](mailto:support@nexusos.top)
* 🐛 **问题反馈与交流：** [GitHub Issues](https://github.com/Tomoyo-Kusosawa/Nexus/issues)

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 协议开源。
