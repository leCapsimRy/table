## 更新日志

`@surely-vue/table` 严格遵循 [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/) 语义化版本规范。

#### 发布周期

- 修订版本号：每周末会进行日常 bugfix 更新。（如果有紧急的 bugfix，则任何时候都可发布）
- 次版本号：每月发布一个带有新特性的向下兼容的版本。
- 主版本号：含有破坏性更新和新特性，不在发布周期内。

---

## 3.0.1

- 🌟 右键菜单新增 主动隐藏方法 `hidePopup` [#116](https://github.com/surely-vue/table/issues/116)
- 🐞 修复浏览器缩放时，滚动条异常问题 [#113](https://github.com/surely-vue/table/issues/113)

## 3.0.0

- 🌟 性能优化，避免 hover 时触发组件 render

## 2.5.3

- 🐞 修复树形结构无法展开问题 [#101](https://github.com/surely-vue/table/issues/101)

## 2.5.2

- 🐞 修复 `rowExpandable` 无法禁用问题 [#99](https://github.com/surely-vue/table/issues/99)

## 2.5.1

- 🐞 修复 `vue@3.2.45` 下，控制台 warning 问题 [#95](https://github.com/surely-vue/table/issues/95)

## 2.5.0

- 🌟 新增暗黑主题 less 文件
- 🌟 新增右键菜单功能
- 🐞 修复表头拖拽时出现滚动条问题

## 2.4.11

`2022-09-29`

- 🐞 修复 scroll.x 失效问题
- 🐞 修复表头滚动条遮挡表格内容问题

## 2.4.10

`2022-09-20`

- 🐞 修复列拖拽导致的显示异常 [#82](https://github.com/surely-vue/table/issues/82)
- 🐞 修复表头分组在虚拟滚动中显示异常

## 2.4.9

`2022-09-01`

- 🐞 修复在 vue 3.2.38 版本下白屏问题 [#79](https://github.com/surely-vue/table/issues/79)
- 🌟 scroll.x 支持动态调整
- 🌟 展开图标和缩进占位添加根节点，方便自定义样式 [#78](https://github.com/surely-vue/table/issues/78)

## 2.4.8

`2022-08-31`

- 🐞 修复 `summaryFixed` 类型提醒问题
- 🌟 优化拖拽列宽时触发排序操作问题
- 🐞 修复 `onSelectAll` 第一个参数错误问题

## 2.4.7

`2022-08-10`

- 🌟 新增 `sticky.topSummary` 用于吸顶头部总计行
- 🐞 修复 `summaryFixed` 类型提醒问题

## 2.4.6

`2022-08-05`

- 🌟 `summaryFixed` 支持顶部吸顶
- 🌟 `rowSelection` columnTitle 支持函数
- 🌟 `selection` text 支持函数
- 🐞 修复滚动宽度自适应问题 [#67](https://github.com/surely-vue/table/issues/67)
- 🐞 修复 `rowSelection` columnTitle 不生效问题 [#64](https://github.com/surely-vue/table/issues/64)

## 2.4.5

`2022-07-27`

- 🐞 修复 `ignoreCellKey` 默认值错误问题

## 2.4.4

`2022-07-27`

- 🌟 新增 `ignoreCellKey` 进一步提升组件复用，提升性能
- 🌟 新增 `showHeaderScrollbar` 显示表头滚动条

## 2.4.3

`2022-07-16`

- 🌟 兼容 antdv 3.3.0-beta

## 2.4.2

`2022-07-15`

- 🐞 修复 scrollX 配置失效问题

## 2.4.1

`2022-07-08`

- 🌟 新增 xVirtual 属性用来控制横向是否虚拟滚动
- 🐞 修复合并列滚动后，合并单元格隐藏问题

## 2.4.0

`2022-06-08`

### 注意：该版本之后需要 Vue 3.2.34 及以上

- 🌟 使用 triggerRef 提升拖拽性能，调整 Vue 最低版本为 3.2.34
- 🐞 修复拖拽后原数据不改变问题 [#45](https://github.com/surely-vue/table/issues/45)
- 🐞 斑马纹、选择、排序时，提升选中行的背景色权重

## 2.3.3

`2022-06-07`

- 🌟 优化 Chrome 102 版本滚动卡顿问题（依然不如其它流畅，但可接受，以及已确认是 Chrome 问题，最终还是要等 chrome 修复了，预计会在 chrome 104 版本修复）
- 🐞 修复展开图标在 Firefox 分屏模式下，图标错位问题

## 2.3.2

`2022-05-25`

- 🐞 修复在 Vue 3.2.34 及以上报错问题

## 2.3.1

`2022-05-14`

- 🐞 修复特殊场景出现多余滚动条问题 [#20](https://github.com/surely-vue/table/issues/20)

## 2.3.0

`2022-05-12`

- 🌟 新增表头自动高度 [#32](https://github.com/surely-vue/table/issues/32)
- 🐞 修复合并列跨度较大时，滚动后丢失问题 [#29](https://github.com/surely-vue/table/issues/29)

## 2.2.3

`2022-04-29`

- 🐞 修复在 antdv2 下，less 报错问题 [#36](https://github.com/surely-vue/table/issues/21)

## 2.2.2

`2022-04-09`

- 🐞 修复翻页后，重置初始值后，无法点击历史状态页码问题

## 2.2.1

`2022-04-01`

- 🐞 修复 `pageSize` 变化时触发两次 change 事件问题 [#18](https://github.com/surely-vue/table/issues/18)
- 🐞 修复启用拖拽后，单元格缓存内容未更新问题 [#21](https://github.com/surely-vue/table/issues/21)

## 2.2.0

`2022-03-19`

- 🌟 优化表格初始化性能
- 🌟 兼容 antdv 3.1 css var
  - 主题色使用 `@surely-primary-color` 继承 `@primary-color`，避免和 antdv 冲突，更改 `@primary-color` 后，`@surely-primary-color` 默认同步更改，除非再次自定义了 `@surely-primary-color`
  - `@surely-primary-color` 是一个 css var，可以方便自定义颜色
- 🌟 新增 `rowHoverDelay` 用于优化表格行 hover 性能 [#17](https://github.com/surely-vue/table/issues/17)

## 2.1.1

`2022-02-19`

- 🔥 支持列拖拽
- 🌟 优化拖拽列宽性能
- 🐞 修复页面滚动后，行拖拽滚动错位问题
- 🐞 修复表头分组 children 为空时，报错问题

## 2.1.0

`2022-02-12`

- 🔥 支持行拖拽排序(树形结构、子表格均支持)
- 🌟 优化单选、多选组件，进一步提升性能（涉及行选择组件、过滤器选择组件）
- 🌟 添加 `allowCancelRadio` 配置是否允许取消单选
- 🌟 优化固定列时，总结栏阴影及边框 1px 错位问题
- 🐞 修复在 safari 下总结栏的固定列单元格出现滚动条问题
- 🐞 修复指定 height 时，总结栏位置错误问题
- 🐞 修复合并列失效问题

## 2.0.10

`2022-01-17`

- 🐞 修复在弹窗中动画引起的高度错误问题

## 2.0.9

`2022-01-16`

- 🐞 修复合并行高度计算错误
- 🌟 优化合并列容错，防止配置不合法导致报错

## 2.0.7

`2021-12-27`

- 🌟 tooltip 为空时不显示

## 2.0.6

`2021-12-26`

- 🌟 新增高性能 tooltip 功能，可自定义单元格提示内容
- 🐞 修复表头 hover 时，表头单元格背景色变成透明问题

## 2.0.5

`2021-12-13`

- 🌟 支持根元素挂载未声明属性，如 class、style 等
- 🌟 调整 customHeaderCell 属性挂载元素
- 🐞 修复在动画下，获取宽高错误导致渲染缺失问题
- 🐞 修复表合计内容换行后背景色缺失问题

#### 文档

- 🌟 新增自定义背景色示例 [查看](https://www.surely.cool/doc/custom#bg-color)

## 2.0.4

`2021-12-12`

- 🌟 隐藏 Mac 下总结栏滚动条
- 🌟 expandRender 支持函数属性
- 🌟 table body 背景色从 cell 调整到 row 上，方便使用 customRow 定义背景色
- 🐞 修复 resizeColumn 受控改变 width 时，宽度不改变问题

## 2.0.3

`2021-12-06`

- 🌟 `resizeColumn` 新增 action 参数，用于判断开始、结束。
- 🌟 `resizeColumn` 新增返回值为 `false` 时受控模式，内部不再自动更改宽度。
- 🌟 新增 `scrollTo`, 控制滚动位置 [demo](/doc/basic#scroll)
- 🐞 修复动态 columns 报错问题 [#8](https://github.com/surely-vue/table/issues/8)

## 2.0.2

`2021-11-26`

- 🌟 新增 CDN 引入支持
- 🌟 优化国际化支持

## 2.0.1

`2021-11-25`

- 🐞 优化 package.json，减少依赖，同时避免引入不同 vue 文件问题

## 2.0

`2021-11-25`

🔥 🔥 🔥 正式发布

## 1.0

该版本不建议使用，可以忽略，我们直接从 2.0 开始
