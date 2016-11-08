---
order: 0
title:
    zh-CN: 基本用法
    en-US: Basic
only: true
---

## zh-CN

简单的 checkbox。

## en-US

Basic usage of checkbox.

````jsx
import { Checkbox, Popover } from 'antd';

function onChange(e) {
  console.log(`checked = ${e.target.checked}`);
}

ReactDOM.render(
<Popover content="hello" trigger="click">
  <Checkbox onChange={onChange}>Checkbox</Checkbox>
</Popover>
, mountNode);
````
