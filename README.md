# floken-designer

自研 SVG 流程画布 + 中国式审批配置面板（仿钉钉配置器 → n8n 式自由画布）。

> 当前为骨架占位，实现见 `流程引擎包文档/02-包需求-floken-designer.md`。

## 硬约束（★）

- **零画布库依赖**：不依赖 bpmn-js / Vue Flow / React Flow / LogicFlow / X6（Q19）。
- **零 UI 框架依赖**：不依赖 Vue / React / Element Plus；只出 **SVG 字符串 + 契约**（选中元素 + schema + onChange），宿主用自己的框架渲染（NFR-D8）。
- 只依赖 `floken-moddle`；`floken-feel/./editor` 为可选 peer（表达式编辑器）。

## 开发

```bash
pnpm install
pnpm build
pnpm verify
```

## 排期

M6 / v1.1+（GA 之后）。v1.0 GA 不含可视化设计器。
