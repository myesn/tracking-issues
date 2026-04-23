# 简介

记录一些正在跟踪的未解决的 issues（虽然已经点了 subscribe，但时间长了有些就找不到了）。

# Open Issues

- `WebStorm 2022.2.1` 不兼容 `eslint@8.23.0`。（将于 `WebStorm 2022.2.2` 修复）
    - [https://youtrack.jetbrains.com/issue/WEB-57089](https://youtrack.jetbrains.com/issue/WEB-57089)
    - [https://github.com/eslint/eslint/issues/16250](https://github.com/eslint/eslint/issues/16250)
- `Vue 3.2x` 无法从其他文件导入 `interface` 作为 `defineProps` 的泛型类型。(将于 `Vue 3.3` 修复）
    - [https://github.com/vuejs/core/issues/4294#issuecomment-1204534444](https://github.com/vuejs/core/issues/4294#issuecomment-1204534444)
- `NestJS` 不支持 `ESM packages`（目前的格式是 `CommonJS`，因为 [sindresorhus 神](https://github.com/sindresorhus) 目前大部分的 package 都是 `Pure ESM`，如果 `NestJS` 不作出更新，很多积极维护的 `modern packages` 就用不了，惨😂）
    - [https://github.com/nestjs/nest/pull/8736](https://github.com/nestjs/nest/pull/8736)
- Docker-Compose shenyu services image not support arm64(Raspberry Pi 4 Model B) architecture（实在不好意思，没有精力协助测试了）
    - [https://github.com/apache/shenyu/issues/3166](https://github.com/apache/shenyu/issues/3166)
- Docker-Compose db(mysql) image not support arm64(Raspberry Pi 4 Model B) architecture（实在不好意思，没有精力协助测试了）
    - [https://github.com/apache/shenyu/issues/3163](https://github.com/apache/shenyu/issues/3163)
- Both Arthas and the container stopped running（实在不好意思，没有精力协助测试了）
    - [https://github.com/alibaba/arthas/issues/2142](https://github.com/alibaba/arthas/issues/2142)
- Why heartbeat interval minimum is 20 seconds?
    - [https://github.com/louislam/uptime-kuma/issues/606](https://github.com/louislam/uptime-kuma/issues/606)
- Allows Dim to manage local video
    - [https://github.com/Dusk-Labs/dim/issues/287](https://github.com/Dusk-Labs/dim/issues/287)
- bug: Migration fails if "logto" DB already exists
    - [https://github.com/logto-io/logto/issues/1844](https://github.com/logto-io/logto/issues/1844)
- feature request: deploy logto under a subpath
    - [https://github.com/logto-io/logto/issues/1969](https://github.com/logto-io/logto/issues/1969)
- tRPC with NestJS Application
    - [https://github.com/trpc/trpc/discussions/1504](https://github.com/trpc/trpc/discussions/1504)
- Windows 系统中 Docker Desktop 启动后，Vmmem 软件占用了很多的内存
    - [High memory usage from VMMEM with docker desktop windows x64 V4.12.0](https://github.com/docker/for-win/issues/12944)
    - [Google 相关内容的搜索结果](https://www.google.com/search?q=high+memory+usage+when+docker+desktop+start)
- ABP CLI `new` 指令中指定 `--ui none` 参数后，会在当前目录下创建一个 `aspnet-core` 子目录
    - [Unnecessary subfolder was created when using abp CLI](https://github.com/abpframework/abp/issues/14579)
- ABP `<abp-input asp-for="RemoteServerId" />` 会在外层包一个 `mb-3` 的 `div` 元素
    - [Remove mb-3 that surrounds abp-input mvc tag helper](https://github.com/abpframework/abp/issues/17948)
- 在 .NET 7 中使用 Office Interop（本地测试发现不支持，只有 .NET Framework 框架的项目才支持）
    - [Access to Office.Interop from .NET Core?](https://github.com/dotnet/core/issues/402)
    - [Office Automation in dotnet core - are there any plans for this?](https://github.com/dotnet/core/issues/409)
- `openapi-generator-cli` 使用 `oneOf` 描述字段时生成了不存在的 `instanceOf<childType>`  函数
    - [[BUG] [TypeScript-Fetch] Incorrectly generated models when using oneOf](https://github.com/OpenAPITools/openapi-generator/issues/14763)
- FastAPI `0.136.0` 版本接口参数 `files: Annotated[list[UploadFile], File()]` 在 `/docs` 中显示为 `string` 而不是文件选择框
    - https://github.com/fastapi/fastapi/pull/15069

# Closed Issues

- nginxconfig.io: Configuration persistence
    - [https://github.com/digitalocean/nginxconfig.io/issues/397](https://github.com/digitalocean/nginxconfig.io/issues/397) 
- `Arco Vue` 组件库中 `<form-item>` 组件的 `content-class` 属性不起作用（实际上 class 名称已追加到 dom 中，但 class 的定义却不见了）
    - [https://github.com/arco-design/arco-design-vue/issues/1587](https://github.com/arco-design/arco-design-vue/issues/1587)
- NextUI 库的动态数据 `<Table>` 组件设置 `classNames` 属性后，再修改数据，整个 `<Table>` 组件都会重新渲染
    - [Table: Rerender the entire table after modifying the data](https://github.com/nextui-org/nextui/issues/2019)
- Strapi 的 `api/users/me?populate=role` 接口不返回 `role` 对象
    - [api/users/me?populate=role not working](https://github.com/strapi/strapi/issues/16217)
- yarn create xxx 时抛错 `detective-postcss@5.1.1: The engine "node" is incompatible with this module`
    - [detective-postcss: The engine "node" is incompatible with this module](https://github.com/strapi/strapi/issues/16106#issuecomment-1484957949)
- 取消 Visual Studio 双击项目后编辑项目文件的行为
    - [We need a setting to define the what double clicking project does](https://github.com/dotnet/project-system/issues/4493#issuecomment-486206732)
