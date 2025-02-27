---
title: InputNumber 数字输入框
description: 数字输入框由增加、减少按钮、数值输入组成。每次点击增加按钮（或减少按钮），数字增长（或减少）的量是恒定的。
isComponent: true
usage: { title: 'Live Demo', description: '' }
spline: form
---

### 双侧调整的数字输入框

已输入的值居中展示，用户可直接在输入框内修改数值，还可以使用输入框左右的箭头按钮增大或减小数值。

{{ center }}

### 右侧调整数值的数字输入框

已输入的值居左展示，用户可直接在输入框内修改数值，还可以使用输入框右侧的箭头按钮增大或减小数值。

{{ left }}

### 小数输入框

可以通过 `decimalPlaces` 来设置小数保留精度，通过 `step` 来设置步进。

{{ step }}

### 格式化展示输入框

通过 `format` 属性格式化数值内容。

{{ format }}

### 不同尺寸的输入框

提供 大、中（默认）、小 3 种数字输入框。

{{ size }}

### 不同状态的输入框

除了禁用 `disabled` 和只读 `readonly` 状态之外，提供 正常（默认）、成功 `success`、警告 `warning`、错误 `error` 4 种状态的输入框设置。

{{ status }}

#### 默认值输入框

通过 `defaultValue` 设置数字输入框的默认值。

{{ default }}

#### 无按钮输入框

仅有输入框，不能用按钮进行数值调整的数字输入框。

{{ normal }}

#### 不同对齐方式的输入框

{{ align }}

### 自适应宽度的输入框

{{ auto-width }}
