---
title: React Container（容器）组件
components: Container（容器）
---

# Container（容器）

<p class="description">容器组件会让您页面的内容水平居中。 这是最基本的布局元素。</p>

虽然容器可以嵌套，但大多数布局不需要嵌套的容器。

## Fluid（流体布局）

您可以通过 `maxWidth` 属性的值来设置一个 fluid 容器的最大宽度。

```jsx
<Container maxWidth="sm">
```

{{"demo": "pages/components/container/SimpleContainer.js", "iframe": true}}

## 固定大小

通过设置`fixed` 属性，您可以设计固定的大小而不是尝试完全流体布局的视口。 max-width 和当前断点的 min-width 则相同。

```jsx
<Container fixed>
```

{{"demo": "pages/components/container/FixedContainer.js", "iframe": true}}