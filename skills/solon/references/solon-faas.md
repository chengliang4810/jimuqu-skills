# solon-faas

仓库路径：`solon-projects/solon-faas`（官方仓库：`https://gitee.com/opensolon/solon`）

用途：Luffy FaaS/脚本函数运行集成。

## 直接子模块

- `solon-faas-luffy` — Luffy 脚本函数运行模块。插件 `org.noear.solon.luffy.integration.LuffyPlugin`。

## 关键源码与 API

- `solon-faas-luffy/src/main/java/org/noear/solon/luffy/integration/LuffyPlugin.java`：插件入口。
- 模块依赖 Luffy executor、Wood、Solon server/logging 等。

## 依赖选择与坑点

- 这是专项 FaaS/脚本运行模块，普通 Web/API 项目不要误引。
- 脚本执行会扩大运行时能力面和安全面，需要单独评估。
