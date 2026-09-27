# @floken-io/designer

> ⚠️ **开发中，尚未发布到 npm。**

自研 SVG 流程画布 + 中国式审批配置面板。

## 设计目标

- **零画布库依赖**：不引入 bpmn-js / Vue Flow / React Flow / LogicFlow / X6
- **零 UI 框架依赖**：不引入 Vue / React / Element Plus；只输出 **SVG 字符串 + 契约**（选中元素 + schema + onChange），宿主用自己的框架渲染
- 只依赖 [`@floken-io/moddle`](https://www.npmjs.com/package/@floken-io/moddle)；[`@floken-io/feel`](https://www.npmjs.com/package/@floken-io/feel) 为可选 peer（表达式编辑器用其 `./editor` 子入口）

## 相关包

| 包 | 用途 |
|---|---|
| [`@floken-io/feel`](https://www.npmjs.com/package/@floken-io/feel) | FEEL 表达式语言 |
| [`@floken-io/moddle`](https://www.npmjs.com/package/@floken-io/moddle) | BPMN 2.0 模型与 XML 转换 |
| [`@floken-io/dmn`](https://www.npmjs.com/package/@floken-io/dmn) | DMN 1.5 决策引擎 |
| `@floken-io/engine` | 流程内核与审批动作（开发中） |
| `@floken-io/designer` | 流程画布与审批配置面板（本包） |

## 许可证

[Apache-2.0](./LICENSE)
