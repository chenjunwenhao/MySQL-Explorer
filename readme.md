<p align="center">
  <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Cdefs%3E%3ClinearGradient id='bg' x1='0' y1='0' x2='1' y2='1'%3E%3Cstop offset='0%25' stop-color='%231e2230'/%3E%3Cstop offset='100%25' stop-color='%2315181b'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='64' height='64' rx='14' fill='url(%23bg)'/%3E%3Cellipse cx='32' cy='20' rx='13' ry='5.5' fill='none' stroke='%234a86f8' stroke-width='2.5'/%3E%3Cpath d='M19 20 L19 42 A13 5.5 0 0 0 45 42 L45 20' fill='none' stroke='%234a86f8' stroke-width='2.5'/%3E%3Cellipse cx='32' cy='42' rx='13' ry='5.5' fill='%234a86f833' stroke='%234a86f8' stroke-width='2.5'/%3E%3Cpath d='M22 18 A11 3.5 0 0 1 42 18' fill='none' stroke='%236ab0ff' stroke-width='1.2' opacity='0.4'/%3E%3C/svg%3E" width="80" alt="MySQL Explorer" />
</p>

<h1 align="center">MySQL Explorer</h1>
<p align="center">只为 MySQL 而生 · 干净利落的数据库管理工具</p>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-Only-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react" alt="React" />
  <img src="https://img.shields.io/badge/Vite-5-646CFF?logo=vite" alt="Vite" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License" />
</p>

---

## 什么让它与众不同

**没有冗余，没有纷杂。只为 MySQL。**

| 特性 | 说明 |
|------|------|
| 🔍 **快速搜索** | 侧边栏模糊搜索，秒级定位任意表、任意字段 |
| ✨ **人性化格式化** | 一键格式化 SQL，可读性优先，不是机械缩进 |
| 📊 **数据直通车** | 双击表名即预览数据，展开即看列信息，无需写 `SELECT *` |
| 🎨 **暗/亮双主题** | DataGrip 风格暗色主题 + 明亮模式，长时间使用不刺眼 |
| ⌨️ **键盘优先** | `Ctrl+F` 搜索库表，`Ctrl+Enter` 执行 SQL，全程键盘流 |

## 快速开始

```bash
git clone git@github.com:chenjunwenhao/MySQL-Explorer.git
cd MySQL-Explorer
npm install
npm run dev
```

浏览器打开 `http://localhost:5173`，输入连接信息，即刻开始。

## 核心功能

- 🗂 **树状导航** — 实例 → 数据库 → 表 / 视图，层次分明
- ✏️ **Monaco 编辑器** — VS Code 同款编辑体验，SQL 语法高亮
- 📋 **DDL 查看** — 右键表名 → View DDL，完整建表语句
- 🔢 **索引查看** — 一键查看表的索引结构
- 🖊 **双击编辑** — 结果集中双击单元格直接修改数据
- 📤 **导出 CSV/JSON** — 查询结果一键导出
- 🗑 **查询历史** — 自动记录，随时复用
- 🔒 **AES-256 加密** — 连接密码本地加密存储
- 💻 **Electron 桌面版** — `npm run electron:dev`

## 项目结构

```
├── src/                 # React 前端
│   ├── App.jsx          # 主应用
│   ├── main.jsx         # 入口
│   └── components/      # 10 个组件
├── server.js            # Express 后端，连接池管理
├── electron/            # Electron 桌面壳
└── vite.config.js       # Vite 配置
```

## 技术栈

React 18 · Vite 5 · Monaco Editor · Express · MySQL2 · Electron

## 参与贡献

欢迎提交 Issue 和 PR。任何改进建议都欢迎。

MIT License © [chenjunwenhao](https://github.com/chenjunwenhao)
