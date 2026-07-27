## Fixed
- **事务改为 Tab 级独立会话**：每个 Query Tab 获取独立的 MySQL 连接，事务不再跨 Tab 共享。修复了多个 Tab 共用一个事务连接的 bug。
- **更新弹窗新增完整更新日志链接**：版本号下方新增 "View full changelog →" 链接，点击跳转 GitHub Release。
