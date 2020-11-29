# 概述

处理 class

# 使用

```javascirpt
// 1. 传入字符串
classnames('bar foo  ');  // bar foo

// 2. 传入对象
classnames({
  bar: true,
  foo: false,
  wrapper: true
}); // bar wrapper

// 3. 传入数组
classnames(['bar', 'foo']); // bar foo

// 4. 传入数组+对象
classnames([
  'bar',
  {
    foo: true,
    tips: false
  },
  'lg'
]); // bar foo lg

```
