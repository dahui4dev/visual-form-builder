# visual-form-builder

[![NPM](https://img.shields.io/npm/v/visual-form-builder.svg)](https://www.npmjs.com/package/visual-form-builder) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

> 可视化表单构建生成工具，主要用于 [visual-form-render](https://github.com/dahui4dev/visual-form-render#associatedformitem) 表单渲染器生成结构化 json 数据使用。

## 安装

```bash
npm install --save visual-form-builder
```

## 使用

- 更详细的使用可参考 `/example/src/app.tsx`

- 运行示例代码

```bash
cd example && yarn && yarn start
```

```tsx
import React from 'react'

import { FormBuilder } from 'visual-form-builder'
import 'visual-form-builder/dist/index.css'

const App = () => {
  return <FormBuilder formName='可视化表单设计工具' />
}

export default App
```

## 待办列表

- [x] 支持构造表单类型
  - [x] input
  - [x] textarea
  - [x] radio
  - [x] select
  - [x] checkbox
  - [x] date
  - [x] span
  - [x] button
  - [x] array
  - [ ] object
  - [ ] file
  - [ ] number
  - [ ] url
  - [ ] color
  - [ ] switch
  - [ ] sider
  - [ ] autocomplate
- [x] 增加前置条件
- [ ] 增加后置条件
- [x] 支持表单栅格化布局

## License

MIT © [dahui4dev](https://github.com/dahui4dev)
