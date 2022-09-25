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
- feature request: Support for non-root path deployments
    - [https://github.com/logto-io/logto/issues/1997](https://github.com/logto-io/logto/issues/1997)
- tRPC with NestJS Application
    - [https://github.com/trpc/trpc/discussions/1504](https://github.com/trpc/trpc/discussions/1504)

# Closed Issues

- `Arco Vue` 组件库中 `<form-item>` 组件的 `content-class` 属性不起作用（实际上 class 名称已追加到 dom 中，但 class 的定义却不见了）
    - [https://github.com/arco-design/arco-design-vue/issues/1587](https://github.com/arco-design/arco-design-vue/issues/1587)
