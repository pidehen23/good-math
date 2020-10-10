# good-math

> JavaScript 精度解决方案

[![npm version](https://img.shields.io/npm/v/good-math.svg)](https://www.npmjs.com/package/good-math)
基于[number-precision](https://github.com/nefe/number-precision)提供了一种解决 JavaScript 的计算中精度丢失问题的方案。

## 发布

#### 提交版本

1. 修订版本号：patch 不定时会进行日常 bugfix 更新。（如果有紧急的 bugfix，则任何时候都可发布）列：`1.0.0 -> 1.0.1`。

```shell
npm run patch
```

2. 次版本号：minor 一个 feature 或多个 feature 同时发布,列：`1.0.0 -> 1.1.0`。

```shell
npm run minor
```

3. 主版本号：major 含有破坏性更新和新特性，不在发布周期内，列：`1.0.0 -> 2.0.0`。

```shell
npm run major
```

#### 发布到 npm

```shell
npm run pub
```
