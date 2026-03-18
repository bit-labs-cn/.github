<div align="center">

<img src="https://avatars.githubusercontent.com/u/190472584?v=4" width="120" style="border-radius: 50%;" />

# Bit Labs · 比特实验室

**Build · Innovate · Transform**

构建模块化、高性能的 Go 语言企业级基础设施

[![GitHub](https://img.shields.io/badge/GitHub-bit--labs--cn-181717?style=flat-square&logo=github)](https://github.com/bit-labs-cn)
[![Email](https://img.shields.io/badge/Email-bit--labs.@qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bit-labs.@qq.com)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](https://github.com/bit-labs-cn/owl/blob/main/LICENSE)

</div>

---

## 关于我们

Bit Labs 是一个专注于 **Go 语言企业级基础设施** 的开源技术团队。我们围绕 Owl 生态，打造从底层框架到上层应用的完整技术体系：

- **模块化架构** — 基于 Service Provider 与依赖注入的松耦合设计
- **开箱即用** — 集成企业开发常用组件，减少重复造轮子
- **全栈覆盖** — 后端框架 + 管理后台 + 前端 UI，一站式解决方案

## 核心项目

<table>
<tr>
<td width="50%" valign="top">

### 🦉 [Owl](https://github.com/bit-labs-cn/owl)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![MIT](https://img.shields.io/github/license/bit-labs-cn/owl?style=flat-square&color=22c55e)
![Stars](https://img.shields.io/github/stars/bit-labs-cn/owl?style=flat-square)

**Go 语言企业级开发框架**

采用依赖注入设计模式的模块化框架，集成了现代 Web 开发所需的丰富组件。

`Gin` `GORM` `Redis` `MQTT` `RabbitMQ` `Casbin` `多云存储` `支付聚合` `OCR` `i18n`

</td>
<td width="50%" valign="top">

### 🔐 [Owl Admin](https://github.com/bit-labs-cn/owl-admin)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Stars](https://img.shields.io/github/stars/bit-labs-cn/owl-admin?style=flat-square)

**企业级后台管理框架**

基于 Owl 核心框架构建的全功能后台管理系统，提供完善的 RBAC 权限体系。

`JWT 认证` `Casbin 授权` `用户/角色/菜单` `组织架构` `字典管理` `操作审计` `OAuth 登录`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 [Owl UI](https://github.com/bit-labs-cn/owl-ui)

![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=flat-square&logo=element&logoColor=white)

**Vue 3 企业级 UI 基础库**

基于 Vue 3 + Element Plus + Tailwind CSS 的企业级前端基础组件与工具库，提供布局、路由、状态管理、国际化等开箱即用能力。

`Vue 3` `Element Plus` `Pinia` `ECharts` `Vditor` `VueUse` `Axios` `vue-i18n`

</td>
<td width="50%" valign="top">

### 🖥️ [Owl Admin UI](https://github.com/bit-labs-cn/owl-admin-ui)

![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**后台管理前端界面**

基于 Owl UI 构建的后台管理系统前端，与 Owl Admin 后端 API 配套，提供完整的管理界面。

`用户管理` `角色权限` `菜单配置` `字典管理` `数据表格` `组织架构`

</td>
</tr>
</table>

## 技术生态

```
┌───────────────────────────────────────────────────────────────┐
│                        Owl 技术生态                            │
├──────────────────────────┬────────────────────────────────────┤
│         后端 (Go)        │           前端 (Vue 3)             │
│                          │                                    │
│   ┌──────────────────┐   │   ┌────────────────────────────┐   │
│   │    Owl Admin     │   │   │      Owl Admin UI          │   │
│   │   (权限管理框架) │   │   │    (后台管理前端界面)      │   │
│   └────────┬─────────┘   │   └─────────────┬──────────────┘   │
│            │              │                 │                  │
│            ▼              │                 ▼                  │
│   ┌──────────────────┐   │   ┌────────────────────────────┐   │
│   │       Owl        │   │   │          Owl UI            │   │
│   │  (核心基础框架)  │   │   │     (前端基础框架)         │   │
│   │                  │   │   │                            │   │
│   │  DI 容器 │ 配置  │   │   │  布局 │ 路由 │ 状态管理   │   │
│   │  路由   │ 中间件 │   │   │  国际化 │ 工具库 │ 主题   │   │
│   │  数据库 │ Redis  │   │   │  ECharts │ Axios │ 编辑器 │   │
│   │  存储   │ 消息队列│   │   │                            │   │
│   │  支付   │ OCR    │   │   └────────────────────────────┘   │
│   └──────────────────┘   │                                    │
│                          │                                    │
└──────────────────────────┴────────────────────────────────────┘
                    ◄──── REST API ────►
```

## 参与贡献

我们欢迎各种形式的参与和贡献：

| 方式 | 说明 |
|------|------|
| 🐛 **报告问题** | 在对应项目中提交 Issue |
| 💻 **提交代码** | Fork 仓库，提交 Pull Request |
| 💡 **功能建议** | 通过 Issue 或 Discussions 提出想法 |
| 📖 **完善文档** | 帮助改进项目文档和示例 |

## 联系我们

- 📧 **Email**: [bit-labs.@qq.com](mailto:bit-labs.@qq.com)
- 💬 **Discussions**: [Owl 社区讨论](https://github.com/bit-labs-cn/owl/discussions)

---

<div align="center">

**⭐ 如果我们的项目对你有帮助，欢迎 Star 支持！**

</div>
