

- 介绍
  - [快速开始](https://maoyantech.github.io/tangdao/introduction/getting-started)
  - [初始化顺序](https://maoyantech.github.io/tangdao/introduction/init-order)
  - [默认输出](https://maoyantech.github.io/tangdao/introduction/default-output)
  - 为什么选择唐刀
- [核心概念](https://maoyantech.github.io/tangdao/core-concepts/index)
- [插件列表](https://maoyantech.github.io/tangdao/plugins/index)
- [API 列表](https://maoyantech.github.io/tangdao/api-reference/index)
- [迁移指南](https://maoyantech.github.io/tangdao/migration-guide/index)

### 为什么选择唐刀

从 redux 原生开发到 Dva 再到 rematch, 社区中存在着丰富的数据流管理解决方案，为什么要选择唐刀呢？

唐刀作为一款以 model 为核心基于 redux + redux-saga 的数据流管理工具，在架构和实现上吸收了社区内众多的解决方案的优势，达到取其精华，去其糟粕，并在其基础上进行创造性改进与扩展。

在使用方式上，唐刀保持了与 Dva 及其相似的 api ，功能上与 Dva 保持一致，可以让 Dva 用户无缝迁移，无须额外的学习和使用成本。此外唐刀将 action 进行了自动维护，因此在代码的维护和开发上唐刀是优于 Dva 的。

在异步处理问题上，唐刀采用的是 redux-saga 方案，并没有采取 async/await 方案。一是降低 redux + redux-saga 和 Dva 项目的迁移成本，二是我们认可 redux-saga 的异步场景处理方案，并对其有着深入挖掘的想法。

在插件机制上，唐刀给予了比 Dva 更加灵活和全面的运用，并且提供了较为丰富和完善的插件。