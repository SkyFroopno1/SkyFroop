# <b>《技术说明文档》</b>

<pre>       Author: 韩霄杰</pre>
# 1. /asserts/webfonts的说明：
css3推出了一个at-rule属性@font-face，来指定特定字体资源的位置、样式特性及其支持的 Unicode 子集。
## 语法

```

@font-face {
  [ font-family: <family-name>; ] ||
  [ src: [ <url> [ format(<string>#) ]? | <font-face-name> ]#; ] ||
  [ unicode-range: <urange>#; ] ||
  [ font-variant: <font-variant>; ] ||
  [ font-feature-settings: normal | <feature-tag-value>#; ] ||
  [ font-variation-settings: normal | [ <string> <number>] # ||
  [ font-stretch: <font-stretch>; ] ||
  [ font-weight: <weight>; ] ||
  [ font-style: <style>; ]
}

```