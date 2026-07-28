## Fixed
- **Hotfix: 修复 v2.4.7 启动崩溃**：TabContent 中 `txStates[tab.id]` 引用了不存在的变量 `tab`，应为 `activeTab?.id`。
