# 简介

记录一些正在跟踪的未解决的 issues（虽然已经点了 subscribe，但时间长了有些就找不到了）。

# Issues

- `WebStorm 2022.2.1` 不兼容 `eslint@8.23.0`。（将于 `WebStorm 2022.2.2` 修复）
    - [https://youtrack.jetbrains.com/issue/WEB-57089](https://youtrack.jetbrains.com/issue/WEB-57089)
    - [https://github.com/eslint/eslint/issues/16250](https://github.com/eslint/eslint/issues/16250)
- `Vue 3.2x` 无法从其他文件导入 `interface` 作为 `defineProps` 的泛型类型。(将于 `Vue 3.3` 修复）
    - [https://github.com/vuejs/core/issues/4294#issuecomment-1204534444](https://github.com/vuejs/core/issues/4294#issuecomment-1204534444)
- `NestJS` 不支持 `ESM packages`（目前的格式是 `CommonJS`，因为 [sindresorhus 神](https://github.com/sindresorhus) 目前大部分的 package 都是 `Pure ESM`，如果 `NestJS` 不作出更新，很多积极维护的 `modern packages` 就用不了，惨😂）
    - [https://github.com/nestjs/nest/pull/8736](https://github.com/nestjs/nest/pull/8736)
