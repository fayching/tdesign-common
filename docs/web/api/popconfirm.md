---
title: Popconfirm 气泡确认框
description: 气泡确认框通常用于不会造成严重后果的二次确认场景，其会在点击元素上弹出浮层进行提示确认。气泡确认框没有蒙层，点击确认框以外的区域即可关闭。
isComponent: true
usage: { title: 'Live Demo', description: '' }
spline: message
---

### 基础气泡确认框

使用说明文字及操作按钮对较简单的操作进行二次确认。

{{ base }}

### 不同图标的气泡确认框

在说明文字之前增加图标，如普通、警示及告警等图标，增强表达以更好的引起用户注意。

{{ icon }}

### 带描述的气泡确认框

在主要说明文字之外增加了操作相关的详细描述，对较复杂的，可能造成疑惑的操作进行详细描述。

{{ describe }}

### 自定义气泡确认框按钮
通过 `confirmBtn` 和 `cancelBtn` 属性来自定义确认和取消按钮，支持传入 Button 组件属性或使用 slot 方式。

{{ button }}

### 控制气泡确认框位置
通过 `popupProps` 可以透传弹窗底层依赖的 Popup 组件所有已支持的属性，比如控制弹窗出现的位置。

{{ inherit }}
