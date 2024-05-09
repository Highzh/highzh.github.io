# Markdown 扩展示例
本页演示了VitePress提供的一些内置的markdown扩展。

## 语法高亮
提供语法高亮显示依赖 [Shiki](https://github.com/shikijs/shiki), 附加功能比如高亮：:

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$
**输入**

````md
```latex
When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$
```
````

**输出**

```latex
$ x=\frac{-b\pm \sqrt{b^2-4ac}}{2a} $
\sqrt{6} 
```

## 自定义容器

**输入**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**输出**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

## 更多

参考vitepress文档markdown中 [full list of markdown extensions](https://vitepress.dev/guide/markdown).
