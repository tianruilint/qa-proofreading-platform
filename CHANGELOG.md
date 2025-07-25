# 变更日志

## [2.0.0] - 2025-07-09

### 新增功能
- **前后端分离架构**：采用React + Flask的现代化架构，提升系统可维护性
- **用户组管理**：实现用户组和管理员组的创建、管理和绑定功能
- **细粒度权限控制**：管理员只能管理绑定的用户组，实现权限隔离
- **溯源功能**：完整记录QA对的校对历史，支持工作追踪和质量管控
- **文件删除权限控制**：用户只能删除自己上传的文件，管理员可删除任何文件
- **智能任务分配**：基于用户组的任务分配机制
- **前端构建系统**：使用Vite构建工具，支持现代化前端开发

### 功能改进
- **取消自动删除**：文件不再自动删除，提高数据安全性
- **UI界面优化**：调整垂直空间利用率，优化图标和按钮位置
- **API接口完善**：提供完整的RESTful API接口
- **部署方式优化**：支持生产环境的前后端分离部署

### 技术更新
- **前端技术栈**：React 18 + Vite + Tailwind CSS + shadcn/ui
- **后端架构**：模块化的Flask应用，支持蓝图和ORM
- **数据库设计**：优化数据模型，支持复杂的权限关系
- **安全增强**：JWT认证，RBAC权限控制，输入验证

### 修复问题
- **前后端部署问题**：修复静态文件服务和SPA路由回退
- **模块导入错误**：修复Python模块路径和依赖问题
- **UI布局问题**：修复垂直空间利用率和组件位置
- **API调用错误**：完善前端API客户端实现

### 文档更新
- **完整部署教程**：详细的生产环境部署指南
- **产品需求文档**：更新功能需求和技术架构说明
- **前端构建指南**：前端开发和构建流程说明
- **项目结构说明**：代码组织和文件结构文档

### 破坏性变更
- **架构变更**：从单体应用改为前后端分离架构
- **数据库结构**：新增用户组、管理员组等表结构
- **API接口**：重新设计API接口，遵循RESTful规范
- **部署方式**：需要Node.js环境进行前端构建

### 迁移指南
从v1.0升级到v2.0需要：
1. 备份现有数据
2. 安装Node.js环境
3. 重新构建前端应用
4. 运行数据库迁移脚本
5. 更新部署配置

## [1.0.0] - 初始版本

### 基础功能
- QA对校对基础功能
- 单文件处理模式
- 简单用户管理
- 基础任务分配
- 文件上传和处理

