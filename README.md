### EntityFrameworkCore

**注意:** 由于本项目一般会试用和支持最新版本的.NET SDK,所以为了保证你能正常编译,请确保运行之前安装当前最新版本的 SDK

**解决 git 不区分大小**

```bash
git config core.ignorecase false
```

[![LICENSE](https://img.shields.io/github/license/EasilyNET/EntityFrameworkCore)](https://img.shields.io/github/license/EasilyNET/EntityFrameworkCore) [![ISSUES](https://img.shields.io/github/issues/EasilyNET/EntityFrameworkCore)](https://img.shields.io/github/issues/EasilyNET/EasilyNET) [![FORKS](https://img.shields.io/github/forks/EasilyNET/EntityFrameworkCore)](https://img.shields.io/github/forks/EasilyNET/EntityFrameworkCore) [![STARS](https://img.shields.io/github/stars/EasilyNET/EntityFrameworkCore)](https://img.shields.io/github/stars/EasilyNET/EntityFrameworkCore) ![GitHub commit activity](https://img.shields.io/github/commit-activity/y/EasilyNET/EntityFrameworkCore) ![GitHub last commit](https://img.shields.io/github/last-commit/EasilyNET/EntityFrameworkCore)

#### EntityFramework Core

| NuGet Package                                                                                 | Version                                                                | Download                                                                | Description                                  |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------- |
| [EasilyNET.Core.Domains](https://www.nuget.org/packages/EasilyNET.Core.Domains)               | ![Nuget](https://img.shields.io/nuget/v/EasilyNET.Core.Domains)        | ![Nuget](https://img.shields.io/nuget/dt/EasilyNET.Core.Domains)        | 提供 Entity、IUnitOfWork、IRepository 等功能 |
| [EasilyNET.Core.Domain.SourceGenerator](https://www.nuget.org/packages/EasilyNET.Core.Domain.SourceGenerator) | ![Nuget](https://img.shields.io/nuget/v/EasilyNET.Core.Domain.SourceGenerator) | ![Nuget](https://img.shields.io/nuget/dt/EasilyNET.Core.Domain.SourceGenerator) | Domains下接口IMayHaveCreator、IHasCreationTime、IHasDeleterId、IHasDeletionTime、IHasModificationTime、IHasModifierId代码生成 |
| [EasilyNET.EntityFrameworkCore](https://www.nuget.org/packages/EasilyNET.EntityFrameworkCore) | ![Nuget](https://img.shields.io/nuget/v/EasilyNET.EntityFrameworkCore) | ![Nuget](https://img.shields.io/nuget/dt/EasilyNET.EntityFrameworkCore) | EntityFrameworkCore 相关，Repository，上下文 |

#### Framework

| NuGet Package                                                                                         | Version                                                                    | Download                                                                    | Description                                 |
| ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| [EasilyNET.AutoInjection.SourceGenerator](https://www.nuget.org/packages/EasilyNET.AutoInjection.SourceGenerator) | ![Nuget](https://img.shields.io/nuget/v/EasilyNET.AutoInjection.SourceGenerator) | ![Nuget](https://img.shields.io/nuget/dt/EasilyNET.AutoInjection.SourceGenerator) |使用 SourceGenerator 代码编译时实现特性和接口注入等多种方式，不使用模块化，要自行实现|

#### 感谢 [JetBrains](https://www.jetbrains.com/shop/eform/opensource) 对本项目的支持!

<img src="https://www.jetbrains.com/shop/static/images/jetbrains-logo-inv.svg" height="100">

## 如何为本项目做出贡献

- Fork 本项目到你自己的仓库.
- 创建一个属于你自己的分支,名字随便你怎么取.
- 然后提交代码到你自己仓库的分支上.
- 然后到本项目创建一个 PR.
- 等待管理员合并 PR 后即可删除掉你自己的仓库.

### Git 贡献提交规范

- 使用 Emoji [参考](https://gitmoji.dev)

| 符号 | 代码                        | 使用场景                              |
| :--: | --------------------------- | ------------------------------------- |
|  🎨  | :art:                       | 改进代码的结构/格式                   |
| ⚡️  | :zap:                       | 提高性能                              |
|  🔥  | :fire:                      | 删除代码或文件                        |
|  🐛  | :bug:                       | 修复错误                              |
| 🚑️  | :ambulance:                 | 关键修补程序                          |
|  ✨  | :sparkles:                  | 引入新功能                            |
|  📝  | :memo:                      | 添加或更新文档                        |
|  🚀  | :rocket:                    | 部署内容                              |
|  💄  | :lipstick:                  | 添加或更新 UI 和样式文件              |
|  🎉  | :tada:                      | 开始一个项目                          |
|  ✅  | :white_check_mark:          | 添加、更新或通过测试                  |
| 🔒️  | :lock:                      | 修复安全问题                          |
|  🔐  | :closed_lock_with_key:      | 添加或更新机密                        |
|  🔖  | :bookmark:                  | 发布/版本标签                         |
|  🚨  | :rotating_light:            | 修复编译器/林特警告                   |
|  🚧  | :construction:              | 工作正在进行中                        |
|  💚  | :green_heart:               | 修复 CI 生成                          |
|  ⬇️  | :arrow_down:                | 降级依赖项                            |
|  ⬆️  | :arrow_up:                  | 升级依赖项                            |
|  📌  | :pushpin:                   | 将依赖项固定到特定版本                |
|  👷  | :construction_worker:       | 添加或更新 CI 生成系统                |
|  📈  | :chart_with_upwards_trend:  | 添加或更新分析或跟踪代码              |
|  ♻️  | :recycle:                   | 重构代码                              |
|  ➕  | :heavy_plus_sign:           | 添加依赖项                            |
|  ➖  | :heavy_minus_sign:          | 删除依赖项                            |
|  🔧  | :wrench:                    | 添加或更新配置文件                    |
|  🔨  | :hammer:                    | 添加或更新开发脚本                    |
|  🌐  | :globe_with_meridians:      | 国际化和本地化                        |
|  ✏️  | :pencil2:                   | 修复拼写错误                          |
|  💩  | :poop:                      | 编写需要改进的不良代码                |
| ⏪️  | :rewind:                    | 还原更改                              |
|  🔀  | :twisted_rightwards_arrows: | 合并分支                              |
| 📦️  | :package:                   | 添加或更新已编译的文件或包            |
| 👽️  | :alien:                     | 由于外部 API 更改而更新代码           |
|  🚚  | :truck:                     | 移动或重命名资源(例如:文件,路径,路由) |
|  📄  | :page_facing_up:            | 添加或更新许可证                      |
|  💥  | :boom:                      | 引入重大更改                          |
|  🍱  | :bento:                     | 添加或更新资产                        |
| ♿️  | :wheelchair:                | 提高可访问性                          |
|  💡  | :bulb:                      | 在源代码中添加或更新注释              |
|  🍻  | :beers:                     | 醉醺醺地编写代码                      |
|  💬  | :speech_balloon:            | 添加或更新文本和文字                  |
|  🗃️  | :card_file_box:             | 执行与数据库相关的更改                |
|  🔊  | :loud_sound:                | 添加或更新日志                        |
|  🔇  | :mute:                      | 删除日志                              |
|  👥  | :busts_in_silhouette:       | 添加或更新参与者                      |
|  🚸  | :children_crossing:         | 改善用户体验/可用性                   |
|  🏗️  | :building_construction:     | 进行体系结构更改                      |
|  📱  | :iphone:                    | 致力于响应式设计                      |
|  🤡  | :clown_face:                | 嘲笑事物                              |
|  🥚  | :egg:                       | 添加或更新复活节彩蛋                  |
|  🙈  | :see_no_evil:               | 添加或更新.gitignore 文件             |
|  📸  | :camera_flash:              | 添加或更新快照                        |
|  ⚗️  | :alembic:                   | 执行实验                              |
| 🔍️  | :mag:                       | 改进搜索引擎优化                      |
|  🏷️  | :label:                     | 添加或更新类型                        |
|  🌱  | :seedling:                  | 添加或更新种子文件                    |
|  🚩  | :triangular_flag_on_post:   | 添加、更新或删除功能标志              |
|  🥅  | :goal_net:                  | 捕获错误                              |
|  💫  | :dizzy:                     | 添加或更新动画和过渡                  |
|  🗑️  | :wastebasket:               | 弃用需要清理的代码                    |
|  🛂  | :passport_control:          | 处理与授权、角色和权限相关的代码      |
|  🩹  | :adhesive_bandage:          | 非关键问题的简单修复                  |
|  🧐  | :monocle_face:              | 数据探索/检查                         |
|  ⚰️  | :coffin:                    | 删除死代码                            |
|  🧪  | :test_tube:                 | 添加失败的测试                        |
|  👔  | :necktie:                   | 添加或更新业务逻辑                    |
|  🩺  | :stethoscope:               | 添加或更新运行状况检查                |
|  🧱  | :bricks:                    | 与基础结构相关的更改                  |
|  🧑‍💻  | :technologist:              | 改善开发人员体验                      |
